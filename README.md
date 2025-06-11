# Simko Chatbot 🤖

Oficiálny AI asistent pre projekt Simko, nasadený pomocou OpenRouter GPT modelu a Flask frameworku.

## 🔧 Funkcie
- Odpovedá na otázky o vízii, technológii a cieľoch projektu Simko
- Používa model `gpt-3.5-turbo` cez OpenRouter API
- Automaticky zapisuje konverzácie do Excel súboru `chat_log.xlsx`
- Pripravené na jednoduché nasadenie cez [Railway](https://railway.app)

## 🚀 Nasadenie cez Railway
1. Vytvor nový GitHub repozitár a nahraj súbory tohto projektu
2. Choď na [railway.app](https://railway.app)
3. Klikni **New Project** → **Deploy from GitHub repo**
4. Vyber tento repozitár
5. Railway automaticky zistí `Procfile` a nasadí aplikáciu
6. Po nasadení budeš mať URL ako `https://simko-chatbot.up.railway.app`

## 🧪 API použitie
- **Endpoint:** `POST /chat`
- **Telo požiadavky:**
```json
{
  "message": "What makes Simko unique?"
}
```
- **Odpoveď:**
```json
{
  "response": "Simko uses a compact drivetrain..."
}
```

## 📁 Súbory v projekte
- `simko_chatbot.py` – hlavná Flask aplikácia
- `requirements.txt` – zoznam závislostí
- `Procfile` – inštrukcia pre Railway, ako spustiť server
- `chat_log.xlsx` – automaticky vytváraný Excel log
- `README.md` – tento popis projektu

## 🛡️ Upozornenie
Nezabudni si v kóde nahradiť svoj OpenRouter API kľúč.

---
