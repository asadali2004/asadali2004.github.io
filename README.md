# GitHub Index Page

A modern, vibrant portfolio page that displays public GitHub repositories for **Asad Ali** (@asadali2004). Features a clean light theme with smooth animations and direct links to GitHub, Portfolio, and LinkedIn.

## ✨ Features
- 🎨 Light and vibrant UI with indigo/pink gradient accents
- 📦 Displays recent public repos (sorted by last update)
- 🔍 Real-time search by repository name or description
- 📊 Repository stats (stars, forks, last updated date)
- 🏷️ Repository topics/tags display
- 📱 Fully responsive design
- 🔗 Quick access to GitHub, Portfolio, and LinkedIn profiles
- ⚡ Smooth hover animations and transitions

## 🎨 Design
- **Theme**: Light and vibrant
- **Colors**: Indigo primary with pink gradient highlights
- **Typography**: System fonts for optimal performance
- **Animations**: Smooth transitions on hover and load

## 📁 Files
- `index.html` - Main HTML structure
- `styles.css` - Separated CSS with modern styling
- `README.md` - Documentation

## 🚀 How to use
1. Open `index.html` in your browser
2. Repositories load automatically from GitHub API
3. Use the search bar to filter repositories
4. Click on repository cards to visit them on GitHub

## ⚙️ Customize
To use for your own GitHub profile, update the username in `index.html`:
```js
const username = "asadali2004"; // Change to your GitHub username
```

## 🔗 Links
- **Portfolio**: [asadali.live](https://asadali.live/)
- **GitHub**: [asadali2004](https://github.com/asadali2004)
- **LinkedIn**: [asadalli](https://www.linkedin.com/in/asadalli/)

## 📝 Notes
- GitHub API has rate limits (60 requests/hour for unauthenticated requests)
- Only non-forked repositories are displayed
- Fetches up to 100 most recently updated repositories
