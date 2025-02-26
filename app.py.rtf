{\rtf1\ansi\ansicpg1252\cocoartf2821
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 import streamlit as st\
import requests\
import pandas as pd\
\
def get_crypto_price(crypto_ids):\
    url = f"https://api.coingecko.com/api/v3/simple/price?ids=\{','.join(crypto_ids)\}&vs_currencies=usd"\
    response = requests.get(url)\
    return response.json() if response.status_code == 200 else \{\}\
\
def calculate_portfolio_value(portfolio, prices):\
    total_value = 0\
    portfolio_data = []\
    for crypto, amount in portfolio.items():\
        price = prices.get(crypto, \{\}).get("usd", 0)\
        value = price * amount\
        total_value += value\
        portfolio_data.append([crypto, amount, price, value])\
    return total_value, portfolio_data\
\
# Streamlit UI\
st.title("\uc0\u55357 \u56522  Krypto-Portfolio-Tracker")\
st.write("Live-Preise von CoinGecko API")\
\
# Beispiel-Portfolio (du kannst es anpassen)\
portfolio = \{"bitcoin": 0.5, "ethereum": 2, "cardano": 100\}\
\
prices = get_crypto_price(portfolio.keys())\
if prices:\
    total_value, portfolio_data = calculate_portfolio_value(portfolio, prices)\
    df = pd.DataFrame(portfolio_data, columns=["Kryptow\'e4hrung", "Menge", "Preis (USD)", "Wert (USD)"])\
    \
    st.dataframe(df)\
    st.subheader(f"\uc0\u55357 \u56496  Gesamtwert: \{total_value:.2f\} USD")\
}