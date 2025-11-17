# 🎯 Phase 3 Usage Guide

## Your AI Movie Recommender Just Got Smarter!

Now your app **learns from you** and gives **personalized recommendations**.

---

## 🆕 What's New in Phase 3

### 1. Rating System ⭐
- Click the stars under any movie to rate it (1-5)
- Your ratings build your taste profile
- Movies rated 4-5 stars teach the AI what you like

### 2. Watchlist 📋
- Click "📋 Watchlist" button to save movies
- Access your watchlist anytime from the header
- Perfect for movies you want to watch later

### 3. User Profile 👤
- Click "👤 Profile" to see your stats:
  - How many movies you've rated
  - Your average rating
  - Your favorite genres
  - Your favorite directors
- See all movies you've rated

### 4. Personalized Recommendations 🎯
- After rating 5+ movies, you'll see personalization badges
- "👤 +X% personal match" shows extra relevance
- The more you rate, the better it gets!

---

## 📖 Step-by-Step Tutorial

### Getting Started (5 minutes)

**Step 1: Search for movies you love**
```
1. Type a movie you like (e.g., "The Dark Knight")
2. Click "Search"
3. Wait 3-5 seconds for AI results
```

**Step 2: Rate movies**
```
1. Hover over the stars under a movie
2. Click to rate (5 stars = love it, 1 star = hate it)
3. You'll see "Rated X stars!" notification
4. Rate at least 5 movies
```

**Step 3: Add to watchlist**
```
1. Click the "📋 Watchlist" button
2. Movie is saved for later
3. Visit watchlist page to see all saved movies
```

**Step 4: Check your profile**
```
1. Click "👤 Profile" in header
2. See your stats and preferences
3. Watch your favorite genres appear!
```

**Step 5: Get personalized recommendations**
```
1. Search for any movie
2. Look for "👤 +X% personal match" badges
3. These movies match YOUR taste!
```

---

## 🎓 How to Train Your AI

### Building a Strong Profile

**Rate Diverse Movies (10-20 ratings)**
```
✅ Rate movies you LOVE (5 stars)
✅ Rate movies you LIKE (4 stars)
✅ Rate movies you're NEUTRAL about (3 stars)
✅ Rate movies you DISLIKE (1-2 stars)

Why? The AI learns what you DO and DON'T like!
```

**Be Honest**
```
Don't rate movies you haven't seen
Rate based on YOUR taste, not critics
The more honest, the better the recommendations
```

**Rate Across Genres**
```
If you like both Action AND Romance:
- Rate action movies you love
- Rate romance movies you love
- The AI will find movies mixing both!
```

---

## 💡 Pro Tips

### Tip 1: The More You Rate, The Smarter It Gets
- **5-10 ratings**: Basic personalization
- **20+ ratings**: Strong personalization  
- **50+ ratings**: Excellent personalization

### Tip 2: Rate 5 Stars for Strong Signals
- Movies rated 5 stars have the biggest impact
- Their genres/directors/actors get huge boosts
- Use 5 stars for movies that define your taste

### Tip 3: Use the Watchlist Wisely
- Add movies that look interesting
- Come back later and rate them after watching
- Helps you discover new movies

### Tip 4: Check Your Profile Regularly
- See which genres dominate
- Discover patterns in your taste
- Notice directors/actors you love

### Tip 5: Compare AI vs Personal Matches
- High AI match = Objectively similar
- High personal match = Matches YOUR specific taste
- Best movies have both!

---

## 🔍 Understanding the Badges

### 🤖 AI Match Badge
```
Example: "🤖 72% match"
Meaning: Based on movie features (genres, cast, plot)
How it works: TF-IDF + Cosine Similarity
```

### 👤 Personal Match Badge
```
Example: "👤 +15% personal match"
Meaning: Bonus for matching your preferences
How it works: Your ratings → genre/director preferences → boost
```

### Combined Power
```
Movie A: 🤖 80% match
Movie B: 🤖 60% match + 👤 +20% personal match
→ Movie B is better FOR YOU (60% + 20% = 80% + personal fit!)
```

---

## 📊 What Your Profile Tracks

### Explicit Data (What You Do)
- ⭐ Movies you rate
- 📋 Movies in your watchlist
- 🎬 Movies you view
- 🎥 Trailers you click
- 🔍 Searches you make

### Learned Preferences (What AI Infers)
- **Genres**: Action, Sci-Fi, Drama, etc. (with scores)
- **Directors**: Christopher Nolan, Quentin Tarantino, etc.
- **Actors**: Top actors from movies you love
- **Keywords**: Themes like "time travel", "heist", "family"

---

## 🎯 Use Cases

### "I want movies like Inception"
```
1. Search "Inception"
2. Rate it 5 stars
3. Rate other Nolan films
4. Future searches boost:
   - Sci-Fi movies
   - Mind-bending plots
   - Christopher Nolan films
```

### "I love superhero movies"
```
1. Rate Marvel/DC movies highly
2. Your profile learns:
   - Action + Adventure + Fantasy
   - Specific directors (Russo Brothers, etc.)
3. Get personalized superhero recommendations
```

### "Find hidden gems in my favorite genre"
```
1. Rate 10-20 movies in that genre
2. Search for a popular movie in the genre
3. Look for lower-rated recommendations with high personal match
4. These are hidden gems matching YOUR taste!
```

---

## 🚀 Advanced Features

### Profile-Based Discovery
After rating many movies, try:
```
1. Search for a genre keyword ("thriller")
2. Get recommendations tuned to your specific taste
3. Discover movies you'd never find otherwise!
```

### Preference Evolution
Your taste changes:
```
- Rate new types of movies
- Your profile adapts
- Recommendations shift to match
- It's a living, learning system!
```

### Cross-Genre Discovery
Love multiple genres?
```
Rate movies from each genre → AI finds blended movies

Example:
- Rate Sci-Fi: The Matrix, Blade Runner
- Rate Comedy: The Hangover, Superbad
- Get: Guardians of the Galaxy (Sci-Fi + Comedy!)
```

---

## 🐛 Troubleshooting

**Q: Recommendations aren't personalized**
```
A: Rate more movies! Need at least 5 ratings for personalization
```

**Q: Wrong genre recommendations**
```
A: Check your profile - which genres have highest scores?
   Rate movies in genres you actually like
```

**Q: Want to reset preferences**
```
A: Delete your file in user_data/ folder
   Or rate movies differently to shift preferences
```

**Q: Watchlist button not working**
```
A: Check browser console for errors
   Make sure JavaScript is enabled
   Refresh the page
```

**Q: Stars not responding**
```
A: Make sure script.js is loaded (check browser console)
   Try refreshing the page
```

---

## 📈 Measuring Success

### Good Signs Your AI is Learning
✅ Personal match badges appear  
✅ Recommended movies match your taste  
✅ Profile shows your favorite genres accurately  
✅ Watchlist grows with interesting movies  
✅ You discover new movies you love  

### Great Profile Stats
🎯 **20+ ratings**  
🎯 **10+ watchlist items**  
🎯 **Top 3 genres** clearly defined  
🎯 **Average rating** 3.5-4.5 (you're selective!)  
🎯 **Favorite directors** identified  

---

## 🎊 Enjoy Your Personalized Movie Experience!

Your AI movie recommender is now a **personal movie advisor** that:
- ✅ Learns from your ratings
- ✅ Tracks your preferences
- ✅ Recommends movies YOU'LL love
- ✅ Gets smarter over time
- ✅ Helps you discover hidden gems

**Start rating movies and watch the magic happen!** 🎬✨

---

**Questions?** Check:
- PHASE_3_COMPLETE.md - Technical details
- README.md - Project overview
- Run `python test_user_preferences.py` to see a demo
