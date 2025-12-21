# GitHub Profile README Setup Guide

## Quick Start

1. **Create your profile repository:**
   - Create a new repository named exactly `YOUR_USERNAME/YOUR_USERNAME` (replace with your GitHub username)
   - Make it public
   - Initialize with a README

2. **Copy the files:**
   - Copy `README.md` to your profile repository
   - Copy `.github/workflows/update-stats.yml` to your profile repository

3. **Update placeholders:**
   - Replace all instances of `YOUR_USERNAME` in `README.md` with your actual GitHub username
   - Update email and social links in the "Connect with me" section
   - Customize your PR stats, favorite anime, current games, etc.

4. **Enable GitHub Actions:**
   - Go to your repository Settings → Actions → General
   - Enable "Workflow permissions" → Read and write permissions
   - The workflow will run daily to update your stats

5. **Set up contribution snake (optional):**
   - The workflow will automatically generate the snake graph
   - It will create an `output` branch with the SVG files
   - The README already references the correct path

## Customization

### Update Personal Stats
- **Powerlifting PRs**: Edit the PR values in the Powerlifting section
- **Current Anime**: Update the "Currently Watching" text
- **Current Game**: Update the "Currently grinding" text
- **Tech Stack**: Modify the languages and tools badges

### Styling
- All styling is in the `<style>` tag at the bottom of README.md
- Background is set to pure black (#000000)
- Accent color is green (#00ff00) for the "live" feel
- Cat emojis are scattered throughout - feel free to add more!

### GitHub Stats
- Stats are automatically pulled from GitHub API via shields.io
- No API keys needed for public repositories
- Stats update automatically via the GitHub Actions workflow

## Features Included

✅ Live coding activity indicators  
✅ GitHub contribution graph  
✅ Language statistics  
✅ Repository statistics  
✅ Streak counter  
✅ Contribution snake animation  
✅ Personality sections (powerlifting, anime, gaming, sports)  
✅ Cat emojis throughout  
✅ Chaotic minimalistic black theme  
✅ Auto-updating via GitHub Actions  

## Notes

- The README uses external services (shields.io, GitHub API) for stats
- Some features require the repository to be public
- The contribution snake requires the workflow to run at least once
- JavaScript in README has limited support on GitHub - most features use static badges/images

Enjoy your new profile! 🐱

