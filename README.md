# app.py
import streamlit as st

st.title("AI Accessibility & Inclusion Assistant")

st.write("Welcome to the AI Accessibility Assistant")

option = st.selectbox(
    "Choose a service",
    ["Text To Speech", "Speech To Text", "Image Description"]
)

st.write("Selected:", option)
