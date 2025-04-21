# 🎧 808 AUTOMATION

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![Spotipy Version](https://img.shields.io/badge/spotipy-2.23.0-green)](https://spotipy.readthedocs.io/)

BeatBoost is your AI-powered productivity sidekick that automagically curates high-energy rap tracks into your Spotify playlist. Perfect for coding marathons, gym sessions, or anytime you need **lyrical fuel for your grind**. 🔥



---

## 🚀 Features

- ⚡ **Auto-Curation**: Smartly adds motivational rap tracks based on your preferences
- 🎛️ **Customizable Vibe**: Choose between focus mode, workout beats, or creative flow
- 🔄 **Daily Updates**: Keep your playlist fresh with automated weekly refreshes
- 🤖 **Surprise Me Mode**: Discover new tracks with AI-powered recommendations
- 🔒 **Privacy First**: No data collection - runs entirely through Spotify's API

---

## 🛠️ Tech Stack

- **Python 3** (Core scripting)
- **Spotipy** (Spotify Web API wrapper)
- **Spotify Web API** (Playlist management and track analysis)
- **argparse** (Command-line interface configuration)

---

## 📦 Installation & Setup

### Prerequisites
- Spotify Premium account
- Python 3.8+ installed
- Developer access to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)

### Step 1: Clone Repository
```bash
git clone https://github.com/your-username/BeatBoost.git
cd BeatBoost
pip install -r requirements.txt

**Configure Spotify API
Create new app in Spotify Developer Dashboard

Add http://localhost:8888/callback as Redirect URI

Create .env file with your credentials:

CLIENT_ID=your_client_id_here
CLIENT_SECRET=your_client_secret_here
REDIRECT_URI=http://localhost:8888/callback

Run BeatBoost
python beatboost.py --mode focus --intensity high**



