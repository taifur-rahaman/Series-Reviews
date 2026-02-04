# Series Reviews - Quick Reference

## 📁 Directory Structure

```
Series-Reviews/
├── README.md                          # Main index with all series organized by genre
├── titles/                            # Individual series review files
│   └── [series_name].md
└── utils/
    ├── series_review_template.md      # Template for new series reviews
    ├── temporal_distribution.md       # Statistics and viewing timeline
    └── covers/                        # Series cover images
        └── [series_name].png
```

## 🎯 Genre Categories

The Series Archives organizes content into the following genres:

1. **🎬 Action & Adventure** - High-octane battles and epic quests
2. **🎭 Drama** - Powerful emotional narratives
3. **😂 Comedy** - Laughter and lighthearted entertainment
4. **🔪 Thriller & Suspense** - Edge-of-your-seat tension
5. **🌌 Sci-Fi & Fantasy** - Otherworldly adventures
6. **❤️ Romance** - Love stories that touch the heart
7. **👻 Horror** - Chills and supernatural scares
8. **🕵️ Mystery & Crime** - Whodunits and investigations
9. **🎯 Anime** - Japanese animated excellence

## 📝 How to Add a New Series

1. **Create a new review file** in `titles/` using the template:
   - Copy `utils/series_review_template.md`
   - Rename to `[series_name].md` (use underscores for spaces)
   - Fill in all metadata and review sections

2. **Add cover image** (optional but recommended):
   - Save cover as `utils/covers/[series_name].png`
   - Update image path in review file

3. **Update README.md**:
   - Add series entry to appropriate genre table
   - Update statistics (total series, hours watched, episodes)
   - Update "Currently Watching" section if applicable

4. **Update temporal_distribution.md**:
   - Add to release year table
   - Update genre statistics
   - Add to viewing timeline
   - Update top rated series if applicable

## 📊 Statistics Tracked

- Total series logged
- Total hours watched
- Total episodes watched
- Series completed vs. in progress
- Currently watching count
- Distribution by genre
- Distribution by release year
- Top rated series
- Monthly viewing activity

## 🌟 Rating System

Series are rated on a 5-star scale:
- ★☆☆☆☆ (1/5) - Poor
- ★★☆☆☆ (2/5) - Below Average
- ★★★☆☆ (3/5) - Average
- ★★★★☆ (4/5) - Good
- ★★★★★ (5/5) - Excellent

Half-stars (⯪) can be used for more nuanced ratings.

## 📺 Status Types

- **Watching** - Currently in progress
- **Completed** - Finished all available episodes
- **On Hold** - Temporarily paused
- **Dropped** - Discontinued watching
- **Plan to Watch** - On the watchlist

---

*Based on the Movie-Reviews repository structure*  
*Created: 4th February 2026*
