# ⚡ Quick Reference Card

## 🚀 Start/Stop

```powershell
# Start the app
cd c:\Users\VRAJKUMA.PATEL\Desktop\MovieRecommenderAI
python app.py

# Stop: Press Ctrl+C in the terminal
```

## 🌐 URLs

- **Main App**: http://127.0.0.1:5000
- **API**: http://127.0.0.1:5000 (POST form)

## 🧪 Testing

```powershell
# Test AI engine
python test_ai.py

# Compare AI vs Basic
python compare_search.py
```

## ⚙️ Configuration

### Toggle AI Mode
Edit `recommender.py` line 4:
```python
USE_AI_RECOMMENDATIONS = True  # or False
```

### API Key
Edit `.env`:
```
TMDB_API_KEY=your_key_here
```

## 📂 Key Files

| File | Purpose |
|------|---------|
| `app.py` | Flask web server |
| `recommender.py` | Main recommendation logic |
| `ai_recommender.py` | AI/ML engine |
| `tmdb_service.py` | TMDb API wrapper |
| `templates/index.html` | UI template |
| `static/style.css` | Styling |

## 🎯 Best Search Examples

- **Sci-Fi**: "Interstellar", "The Matrix", "Blade Runner"
- **Action**: "John Wick", "Die Hard", "Mad Max"
- **Drama**: "The Shawshank Redemption", "Forrest Gump"
- **Horror**: "Get Out", "A Quiet Place", "The Conjuring"
- **Comedy**: "The Hangover", "Superbad", "Bridesmaids"
- **Animation**: "Toy Story", "Spider-Verse", "Coco"

## 🔧 Troubleshooting

### No results?
- Check movie title spelling
- Try a more popular movie
- Ensure server is running

### Slow results?
- AI takes 3-5 seconds (normal!)
- First search builds model (slower)

### Errors?
- Check terminal for logs
- Verify `.env` has API key
- Check internet connection

### Server won't start?
```powershell
# Check if port 5000 is in use
netstat -ano | findstr :5000

# Kill process if needed (replace PID)
taskkill /PID <process_id> /F
```

## 🎨 UI Elements

- **🤖 Badge**: AI match percentage
- **⭐ Rating**: TMDb rating /10
- **Watch Trailer**: YouTube link
- **Pagination**: Previous/Next buttons

## 📊 Match Scores

- **80%+**: Extremely similar
- **60-79%**: Very similar
- **40-59%**: Similar
- **30-39%**: Somewhat related
- **<30%**: Not shown (filtered)

## 🔄 Git Commands

```powershell
# Initialize repo (if not done)
git init
git add .
git commit -m "AI movie recommender complete"

# Push to GitHub
git remote add origin <your-repo-url>
git push -u origin main
```

## 📦 Dependencies

Install all:
```powershell
pip install -r requirements.txt
```

Individual:
```powershell
pip install flask requests python-dotenv numpy scikit-learn
```

## 🐛 Debug Mode

Already enabled in `app.py`:
```python
app.run(debug=True)
```

- Auto-reloads on file changes
- Shows detailed errors
- Interactive debugger

## 📈 Performance Tips

1. First search is slower (builds models)
2. Subsequent searches are faster
3. AI mode: 3-5 seconds
4. Basic mode: <1 second

## 🎓 Learning Resources

- **Flask**: https://flask.palletsprojects.com/
- **scikit-learn**: https://scikit-learn.org/
- **TMDb API**: https://developers.themoviedb.org/
- **TF-IDF**: https://en.wikipedia.org/wiki/Tf-idf
- **Cosine Similarity**: https://en.wikipedia.org/wiki/Cosine_similarity

## 🎯 Next Phase

Ready for **Phase 3: User Learning**?
- User accounts
- Rating system
- Preference tracking
- Personalized recommendations

Just say the word! 🚀

## 📞 Quick Help

| Issue | Solution |
|-------|----------|
| Import error | Run `pip install -r requirements.txt` |
| API error | Check `.env` has valid key |
| Server error | Check terminal for stack trace |
| No matches | Try more popular movie title |
| Slow response | Normal for AI (3-5 sec) |

---

**Your AI Movie Recommender is ready!** 🎬✨

Save this card for quick reference while working on the project.
