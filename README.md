# Golf Factors

Predicting your Tournament Winners with Course Intelligence

## URLs for this Project

### Repository URL
- **GitHub Repository**: https://github.com/kdub2008/GolfFactors

### GitHub Pages URL (Once Enabled)
- **Live Website**: https://kdub2008.github.io/GolfFactors/GolfFactors.html
  - Note: GitHub Pages needs to be enabled first (see instructions below)
  - Alternative: Rename `GolfFactors.html` to `index.html` to use https://kdub2008.github.io/GolfFactors/

### Local Access
If you've cloned the repository locally, you can open the file directly:
- File path: `GolfFactors.html`
- Open in browser: `file:///path/to/your/local/GolfFactors/GolfFactors.html`

## About Golf Factors

Golf Factors is an advanced analytics tool for predicting tournament winners by matching golfer statistics with course profiles.

### How It Works

Our system analyzes key performance metrics:
- Driving accuracy
- Approach play
- Putting consistency
- Scrambling ability

These metrics are weighted based on the specific demands of each course.

### Fit Score Calculation
- **65%** - Course-specific stats (varies by venue)
- **25%** - Recent Top 10 finishes
- **10%** - Consecutive cuts made

This balance ensures we identify golfers who both fit the course and are playing well right now.

## Features

- Select from various PGA Tour events including:
  - **Majors**: Masters, U.S. Open, PGA Championship, The Open Championship
  - **Signature Events**: Players Championship, Arnold Palmer Invitational, and more
  - **Fall & Spring/Summer Events**: Various PGA Tour stops

- View predicted winners based on statistical analysis
- See weekly results and prediction accuracy

## Usage

Simply open the `GolfFactors.html` file in a web browser:

1. Choose a tournament from the dropdown menu
2. View the predicted top golfers for that specific course
3. See how course characteristics match with player strengths

## Enabling GitHub Pages

To make this website accessible online via GitHub Pages, follow these steps:

1. Go to your repository: https://github.com/kdub2008/GolfFactors
2. Click on **Settings**
3. Navigate to **Pages** in the left sidebar
4. Under **Source**, select the branch (usually `main` or `copilot/define-url-endpoint`)
5. Select **/ (root)** as the folder
6. Click **Save**
7. Your site will be published at:
   - **With current filename**: https://kdub2008.github.io/GolfFactors/GolfFactors.html
   - **Or rename to index.html** for simpler URL: https://kdub2008.github.io/GolfFactors/

Note: It may take a few minutes for the site to become available after enabling GitHub Pages.

### Recommended: Rename for cleaner URL
For a cleaner URL, consider renaming `GolfFactors.html` to `index.html`:
```bash
git mv GolfFactors.html index.html
git commit -m "Rename to index.html for GitHub Pages"
git push
```
Then your site will be accessible at: https://kdub2008.github.io/GolfFactors/

## Technical Details

- **Technology**: Pure HTML/CSS/JavaScript
- **No dependencies**: Static site, no build process required
- **Mobile responsive**: Works on all device sizes

## Data Source

Professional predictions powered by statistical analysis of PGA Tour player performance metrics.

---

🏌️ Data-driven golf analytics
