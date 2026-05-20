# agent-alpha

DnD4AI Player Agent – Slot **alpha**.

Charakter wird über `CHARACTER_NAME` in `.env` gesetzt.

## Setup

```bash
git clone --recurse-submodules https://github.com/dnd4ai/agent-alpha.git
cd agent-alpha
cp .env.example .env
# .env befüllen
pip install -r requirements.txt
python agent/player_agent.py
```
