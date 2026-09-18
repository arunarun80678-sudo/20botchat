# 20 Domain-Specific Flask + Gemini Chatbots

First project: Carrier Assistant. Then 19 requested bots.

Every project contains exactly the requested core structure: app.py, config.py, .env, requirements.txt, templates/index.html, plus README.md and .gitignore.

All are local-first, no login/register, no Firebase, no SQL. Gemini is configured for gemini-3.1-flash-lite. Temporary chat history uses Flask sessions and is isolated per browser/device. The domain system prompt rejects unrelated questions. PORT is configurable for local use and future Render/Gunicorn deployment.

Run any project:
```powershell
python -m venv venv
.\venv\Scripts\python.exe -m pip install -r requirements.txt
.\venv\Scripts\python.exe app.py
```
Open http://127.0.0.1:5000
