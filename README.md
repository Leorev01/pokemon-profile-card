# 🎮 Pokémon-Style GitHub Profile Cards

Generate beautiful, animated profile cards for your GitHub README with Pokémon-inspired themes! Each card shows your GitHub stats with custom type icons and gradients.

## ✨ Features

- **18 Pokémon Types**: Choose from normal, fire, water, electric, grass, ice, fighting, poison, ground, flying, psychic, bug, rock, ghost, dragon, dark, steel, fairy
- **Real-time Stats**: Shows your actual GitHub followers, stars, repos, and activity
- **Dynamic Content**: Updates automatically with your latest GitHub data
- **SVG Format**: Perfect for embedding in GitHub READMEs
- **No Screenshots Needed**: Direct SVG embedding!

## 🚀 Quick Start

### Option 1: Direct API Embedding (Recommended)

Add this to your GitHub profile README:

```markdown
![My GitHub Stats](https://profile-card-ten-green.vercel.app/api/card?username=YOUR_GITHUB_USERNAME&type=fire)
```

**Examples:**
```markdown
<!-- Fire type card -->
![GitHub Stats](https://profile-card-ten-green.vercel.app/api/card?username=octocat&type=fire)

<!-- Water type card -->
![GitHub Stats](https://profile-card-ten-green.vercel.app/api/card?username=octocat&type=water)

<!-- Dragon type card -->
![GitHub Stats](https://profile-card-ten-green.vercel.app/api/card?username=octocat&type=dragon)
```

### Option 2: Preview First

Visit the website to preview your card before embedding:
```
https://profile-card-ten-green.vercel.app/?username=YOUR_GITHUB_USERNAME&type=fire
```

## 🎨 Available Types

| Type | Example | Type | Example |
|------|---------|------|---------|
| **Normal** | `type=normal` | **Fire** | `type=fire` |
| **Water** | `type=water` | **Electric** | `type=electric` |
| **Grass** | `type=grass` | **Ice** | `type=ice` |
| **Fighting** | `type=fighting` | **Poison** | `type=poison` |
| **Ground** | `type=ground` | **Flying** | `type=flying` |
| **Psychic** | `type=psychic` | **Bug** | `type=bug` |
| **Rock** | `type=rock` | **Ghost** | `type=ghost` |
| **Dragon** | `type=dragon` | **Dark** | `type=dark` |
| **Steel** | `type=steel` | **Fairy** | `type=fairy` |

## 🖼️ Visual Examples

Here's what the different type cards look like:

<div style="display: flex; flex-wrap: wrap; gap: 12px; justify-content: flex-start;">
  <img src="assets/screenshots/normal.png" alt="Normal Type Card" width="200" />
  <img src="assets/screenshots/fire.png" alt="Fire Type Card" width="200" />
  <img src="assets/screenshots/water.png" alt="Water Type Card" width="200" />
  <img src="assets/screenshots/electric.png" alt="Electric Type Card" width="200" />
  <img src="assets/screenshots/grass.png" alt="Grass Type Card" width="200" />
  <img src="assets/screenshots/ice.png" alt="Ice Type Card" width="200" />
  <img src="assets/screenshots/fighting.png" alt="Fighting Type Card" width="200" />
  <img src="assets/screenshots/poison.png" alt="Poison Type Card" width="200" />
  <img src="assets/screenshots/ground.png" alt="Ground Type Card" width="200" />
  <img src="assets/screenshots/flying.png" alt="Flying Type Card" width="200" />
  <img src="assets/screenshots/phsycic.png" alt="Psychic Type Card" width="200" />
  <img src="assets/screenshots/bug.png" alt="Bug Type Card" width="200" />
  <img src="assets/screenshots/rock.png" alt="Rock Type Card" width="200" />
  <img src="assets/screenshots/ghost.png" alt="Ghost Type Card" width="200" />
  <img src="assets/screenshots/dragon.png" alt="Dragon Type Card" width="200" />
  <img src="assets/screenshots/dark.png" alt="Dark Type Card" width="200" />
  <img src="assets/screenshots/steel.png" alt="Steel Type Card" width="200" />
  <img src="assets/screenshots/fairy.png" alt="Fairy Type Card" width="200" />
</div>

*Note: These are example screenshots. Your actual card will show your real GitHub data!*

## 📊 What Your Card Shows

Each card displays:
- **Experience Level**: Junior/Mid/Senior/Lead Dev (calculated from your activity)
- **Followers Count**: Your GitHub followers
- **Skills**: Top programming languages from your repos
- **Special Abilities**: 
  - ⭐ Total stars across all your repos
  - 📦 Number of public repositories
- **Recent Activity**: Your latest GitHub activity
- **Profile Picture**: Your GitHub avatar
- **Type Icon**: Pokémon-style type icon matching your chosen theme

## 🔧 Customization

### Change Your Type
Replace `type=fire` with any of the 18 available types:
```markdown
![Stats](https://profile-card-ten-green.vercel.app/api/card?username=yourname&type=water)
```

### Use Different Username
Replace `username=yourname` with any GitHub username:
```markdown
![Stats](https://profile-card-ten-green.vercel.app/api/card?username=octocat&type=dragon)
```

## 🎯 Perfect for GitHub Profiles

This is ideal for:
- **GitHub Profile READMEs**: Add to your `username/username` repository
- **Portfolio Websites**: Embed in your personal website
- **Developer Portfolios**: Show off your GitHub stats in style
- **README Files**: Add to project READMEs to show your stats

## 🚀 Deploy Your Own

1. **Fork this repository**
2. **Deploy to Vercel** (or your preferred platform)
3. **Update the domain** in the examples above
4. **Share with others!**

## 📝 Example GitHub Profile README

```markdown
# Hi there 👋

![My GitHub Stats](https://profile-card-ten-green.vercel.app/api/card?username=yourname&type=fire)

## About Me
- 🔥 I love coding and building things
- 🚀 Currently working on awesome projects
- 📚 Always learning new technologies

## My Projects
- [Project 1](link)
- [Project 2](link)
- [Project 3](link)
```

## ⚠️ Rate Limits

This service uses GitHub's public API, which has rate limits:
- **Unauthenticated**: 60 requests per hour
- **Authenticated**: 5,000 requests per hour

If you hit rate limits, the card will show an error message.

## 🛠️ Technical Details

- **Built with**: Node.js, Express, SVG
- **Deployment**: Vercel serverless functions
- **API**: RESTful endpoint serving SVG images
- **CORS**: Enabled for cross-origin embedding

## 🤝 Contributing

We love contributions! Here are some ways you can help:

### 🎨 Add New Features
- **New Pokémon types** - create new type themes
- **Custom backgrounds** - add new gradient patterns
- **Additional stats** - show more GitHub data
- **Animations** - add CSS animations to the cards

### 🐛 Report Issues
- Found a bug? [Open an issue](https://github.com/yourusername/animated-profile-stats/issues)
- Have a feature request? [Let us know](https://github.com/yourusername/animated-profile-stats/issues)

### 📝 Improve Documentation
- Better examples
- More screenshots
- Clearer instructions
- Translation help

### ⚡ Performance & Code
- Optimize API responses
- Improve error handling
- Add tests
- Code cleanup

**See [CONTRIBUTING.md](https://github.com/yourusername/animated-profile-stats/blob/main/CONTRIBUTING.md) for detailed guidelines!**

## 📄 License

MIT License - feel free to use and modify!

---

**Made with ❤️ for the GitHub community**
