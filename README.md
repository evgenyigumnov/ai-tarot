# ai-tarot

AI-Tarot is a Python-based tool to generate custom Tarot card illustrations using OpenAI's image models. Define your desired art style, run the script with your API key, and get a full deck of uniquely styled Tarot cards. Perfect for creatives, game designers, or spiritual enthusiasts.

Already generated tarot cards: [https://evgenyigumnov.github.io/ai-tarot](https://evgenyigumnov.github.io/ai-tarot)

## Installation
```
pip install -r requirements.txt
```
## Usage
Edit `generate-cards.py` and set style of tarot cards: 
```
style = "Funny, comic style"
```

## Run
```
python generate-cards.py -k YOUR_OPENAI_API_KEY
```

## Result
Check result in folder `generated-cards`. Remove files you don't like and launch again the script for regeneration deleted cards.

## Share your Tarot deck via pull request
All new cards will be added to the repository in folder `static/deck/DECK_ID`.
