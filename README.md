import os
from google import genai
from dotenv import load_dotenv

# .env فائل سے کلید لوڈ کریں
load_dotenv()
api_key = os.getenv("GEMINI_API_KEY")

client = genai.Client(api_key=api_key)

# باقی کوڈ یہاں لکھیں...
