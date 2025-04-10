# Lyrics Chatbot Made By Nazeer, Tarun, Surya
A web-based chatbot built using Flask and JavaScript that fetches full song lyrics using the Genius API. Supports both English and Hindi songs.

---
## INSTALL THESE(if you don't have)
 pip install -r requirements.txt
 ->run by pasting python backend.py in your terminal(optional)


##  How to Use

Just type your message in the chatbox using this format:

```
Shape of You by Ed Sheeran
Tum Hi Ho by Arijit Singh
```

-  Make sure to use *Song Name by Artist Name*
-  You can also just say things like “hi” or “give me lyrics” and the bot will respond!
-  If you ask anything else, the bot will politely say it's only made for lyrics.
- Note: Hindi songs are limited, as Genius doesn't have copyright issues.
---

##  Tools Used

- Python + Flask (backend)
- JavaScript + HTML (frontend)
- Genius API for lyrics
- BeautifulSoup for web scraping

---

##  Project Structure

```
lyrics-chatbot/
├── backend.py
├── frontend.html
├── script.js
├── .env               
├── requirements.txt   
└── README.md
```

---

##  Credits
THANK YOU!!
Made by Nazeer, Tarun, Surya.
Uses the [Genius API](https://genius.com) for fetching lyrics.
