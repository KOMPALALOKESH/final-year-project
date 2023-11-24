# final-year-project

!mkdir db
!mkdir models
!mkdir docs

!python ingest.py

!streamlit run chatbot_app.py
(!wget -q -O - ipv4.icanhazip.com)
(!streamlit run chatbot_app.py & npx localtunnel --port 8501)
