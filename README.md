# Retail-data-Analytics-Project-Python-SQL-
import kaggle
import pandas as pd
import sqlalchemy as sal

Connecting Pandas to SQL--
engine = sal.create_engine('mssql://USER/Database?DRIVER_NAME')
conn=engine.connect()
