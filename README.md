# ETL-Pipeline---Web-scraping
## Overview
Your task is to scrape basketball, baseball, and football data from the HotStreak platform (https://hs3.hotstreak.gg/) and structure it according to the specified data models.
Target Data Models

Python
from datetime import datetime
from typing import List

class Odd:
    id: str
    market: str
    player_name: str
    decimal_odds: float

class Match:
    id: str
    home_team: str
    away_team: str
    start_time: datetime
    league: str
    odds: List[Odd]
