# Golf Factors

Predicting your Tournament Winners with Course Intelligence

## URLs for this Project

### Repository URL
- **GitHub Repository**: https://github.com/kdub2008/GolfFactors

### GitHub Pages URL (Once Enabled)
- **Live Website**: https://kdub2008.github.io/GolfFactors/
  - Note: GitHub Pages needs to be enabled first (see instructions below)

### Local Access
If you've cloned the repository locally, you can open the file directly:
- File path: `index.html`
- Open in browser: `file:///path/to/your/local/GolfFactors/index.html`

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

Simply open the `index.html` file in a web browser:

1. Choose a tournament from the dropdown menu
2. View the predicted top golfers for that specific course
3. See how course characteristics match with player strengths

## Enabling GitHub Pages

To make this website accessible online via GitHub Pages, follow these steps:

1. Go to your repository: https://github.com/kdub2008/GolfFactors
2. Click on **Settings**
3. Navigate to **Pages** in the left sidebar
4. Under **Source**, select the branch you want to deploy (e.g., `main` or the branch with your latest changes)
5. Select **/ (root)** as the folder
6. Click **Save**
7. Your site will be published at: https://kdub2008.github.io/GolfFactors/

Note: It may take a few minutes for the site to become available after enabling GitHub Pages.

## Technical Details

- **Technology**: Pure HTML/CSS/JavaScript
- **No dependencies**: Static site, no build process required
- **Mobile responsive**: Works on all device sizes

## Data Source

This is a demonstration application showing how golf analytics could work. The player statistics and predictions shown are examples for illustrative purposes. 

For a production version, data would typically be sourced from:
- Official PGA Tour statistics (SG: Strokes Gained metrics)
- Golf statistics providers (DataGolf, FantasyNational, etc.)
- Historical tournament performance data

The current version serves as a framework for implementing a real-time golf prediction system with actual statistical data.

---

🏌️ Data-driven golf analytics
