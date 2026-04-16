# Describe-base-de-dato
import pandas as pd

data = {
    "edad": [23, 45, 31, 35, 62],
    "salario": [1000, 2000, 1500, 1800, 2500]
}

df = pd.DataFrame(data)

print(df.describe())
