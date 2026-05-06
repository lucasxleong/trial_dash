import streamlit as st
import pandas as pd
import numpy as np

st.set_page_config(page_title="My Live Dashboard", layout="wide")

st.title("🚀 My First Live Dashboard")
st.write("This site is live and hosted for free!")

# Create some dummy data
data = pd.DataFrame(
    np.random.randn(20, 3),
    columns=['Sales', 'Marketing', 'Product']
)

# Create layout columns
col1, col2 = st.columns(2)

with col1:
    st.subheader("Monthly Metrics")
    st.line_chart(data)

with col2:
    st.subheader("Data Overview")
    st.write(data.describe())

st.success("Connected to live data!")
