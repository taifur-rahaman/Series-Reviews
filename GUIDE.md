# Series Reviews - Quick Reference

## 📁 Directory Structure

```
Series-Reviews/
├── README.md                          # Main index with all series organized by genre
├── titles/                            # Series directories
│   └── [series_name]/                 # Directory for a specific series
│       ├── season_1.md                # Review for Season 1
│       └── season_2.md                # Review for Season 2
└── utils/
    ├── season_review_template.md      # Template for new season reviews
    ├── temporal_distribution.md       # Statistics and viewing timeline
    └── covers/                        # Series cover images
        └── [series_name].png
```

## 🎯 Genre Categories

- **Action & Adventure**
- **Drama**
- **Comedy**
- **Thriller & Suspense**
- **Sci-Fi & Fantasy**
- **Romance**
- **Horror**
- **Mystery & Crime**

## 🎯 Anime Categories

- **Isekai**
- **Slice of Life**
- **Gourmet**
- **Action & Fantasy**
- **Drama & Romance**

## 📝 How to Add a New Series/Season

1. **Create a series directory** in `titles/`:
   - Name it `[series_name]` (e.g., `titles/bhay/`)

2. **Create a season review file**:
   - Copy `utils/season_review_template.md`
   - Save as `titles/[series_name]/season_[x].md`
   - Fill in metadata and review sections

3. **Add cover image**:
   - Save cover as `utils/covers/[series_name].png`
   - Update image path in review file (`../../utils/covers/[series_name].png`)

4. **Update README.md**:
   - Add entry linking to the specific season file
   - Format: `[Series Name (Season X)](titles/[series_name]/season_[x].md)`
   - **Note**: You can list a series under multiple genre categories if it fits.

5. **Update temporal_distribution.md**:
   - Add to release year and viewing timeline

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
