# 🎬 Quick Start Guide

## Getting Started

1. **Open the app**: Navigate to http://127.0.0.1:5000
2. **Search for a movie**: Type a movie name (e.g., "Interstellar", "The Matrix", "Inception")
3. **Watch the AI work**: Results will show with match percentages
4. **Browse results**: Click on trailers, explore recommendations

## Try These Searches

### Sci-Fi Movies
- "Interstellar" → Get space exploration movies
- "The Matrix" → Get cyberpunk/reality-bending movies
- "Blade Runner" → Get dystopian sci-fi

### Action Movies
- "John Wick" → Get stylized action movies
- "Die Hard" → Get classic action movies
- "Mad Max" → Get post-apocalyptic action

### Drama Movies
- "The Shawshank Redemption" → Get prison/redemption dramas
- "Forrest Gump" → Get life story dramas
- "Good Will Hunting" → Get character-driven dramas

### Marvel/DC
- "Avengers" → Get superhero ensemble movies
- "The Dark Knight" → Get darker superhero movies
- "Guardians of the Galaxy" → Get space adventure superhero movies

## Understanding Match Scores

- **80%+**: Nearly identical style, genre, and feel
- **60-79%**: Very similar with shared themes
- **40-59%**: Related with some common elements
- **30-39%**: Loosely related or shared genre
- **Below 30%**: Filtered out (not shown)

## Features to Look For

1. **🤖 AI Badge**: Shows the match percentage for each recommendation
2. **⭐ Rating**: TMDb user rating out of 10
3. **Release Date**: When the movie came out
4. **Overview**: Short plot description
5. **Watch Trailer**: Direct link to YouTube trailer

## Toggle AI Mode

If you want to see the difference:

1. Open `recommender.py`
2. Change line 4:
   ```python
   USE_AI_RECOMMENDATIONS = False  # Basic search
   ```
3. Save and the server will auto-reload
4. Search again to see basic results without AI

## What Makes This AI Smart?

Unlike basic keyword search, our AI:
- Reads and understands movie plots
- Analyzes who directed and starred in the movie
- Identifies themes and genres
- Finds patterns across thousands of movies
- Learns what makes movies similar beyond just their titles

## Next Features Coming

- 👤 User profiles and preference learning
- ⭐ Rate movies to get better recommendations
- 📝 Watchlist to save movies for later
- 🔥 Trending movies section
- 🎯 Multi-movie recommendations ("Find movies like these 3")
- 🎨 Movie detail pages with full cast/crew

## Tips

- **Be specific**: "Christopher Nolan movies" works better than just "Nolan"
- **Use full titles**: "The Lord of the Rings" better than "LOTR"
- **Try franchises**: Search for one movie in a series to find similar franchises
- **Explore**: The AI might surprise you with unexpected but relevant matches!

## Troubleshooting

**No results?**
- Check your spelling
- Try a more popular movie title
- Make sure the Flask server is running

**Slow results?**
- AI recommendations take 3-5 seconds (analyzing features)
- First search is slower (building models)
- This is normal and worth the wait for better results!

**Error messages?**
- Check the terminal for detailed error logs
- Make sure your `.env` file has a valid TMDb API key
- Internet connection required for TMDb API

## Have Fun! 🎉

Explore movies, find hidden gems, and discover your next favorite film!
