# Prompty - GEO Monitoring Dashboard

Streamlit dashboard that benchmarks brand & product visibility across multiple 
LLMs by running structured prompt suites per category. Built for Generative 
Engine Optimization (GEO) analysis in B2B AdTech.

## What it does
- Queries **GPT-3.5-Turbo**, **Gemini**, and **DeepSeek** with category-specific 
  prompt batches
- Surfaces **brand mention frequency**, **top product rankings**, and 
  **key buying signals** in an interactive dashboard
- Generates a natural-language summary of buzzwords and purchase drivers per 
  category
- Exposes raw prompt/response data for inspection

## Built with
- Python · Streamlit · Pandas
- OpenAI API · Google Gemini API · DeepSeek API

## Background
Built during the **Harvard Undergraduate Ventures TECH Summer Program** for 
ReachFaster, a B2B AdTech startup, to help clients understand how their brand 
appears in AI-generated search results.

## Run locally
```bash
git clone https://github.com/aritheboss18785/Prompty
cd Prompty
pip install -r requirements.txt
# Add your API keys to .env
streamlit run app.py
```
