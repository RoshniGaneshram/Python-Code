# ELO Merchandising
import pandas as pd
import numpy as np

tr = pd.read_csv('D:/MSMA/DataScience/Elo/train_clean.csv')
del tr['Unnamed: 0']
del tr['first_active_month']
del tr['card_id']
y=tr.target
del tr['target']
X=tr


