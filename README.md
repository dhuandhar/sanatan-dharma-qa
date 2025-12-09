# Sanatana Dharma Q&A for Youth

A beautiful, mobile-friendly web application featuring questions and answers about Sanatana Dharma (Hinduism) from a youth perspective.

## Features

- 📱 **Mobile-Friendly**: Works perfectly on all devices, especially iPhone
- 🎨 **Beautiful Design**: Traditional Indian colors and elegant typography
- 🔍 **Category Filtering**: Filter questions by topic (Hinduism, God, Rituals, Marriage, etc.)
- 📜 **Scrollable Cards**: Easy-to-read Q&A format with smooth scrolling
- ⬆️ **Back to Top**: Quick navigation button
- 🌐 **No Backend Required**: Pure HTML/CSS/JavaScript

## Live Demo

Once hosted on GitHub Pages, your app will be available at:
`https://YOUR-USERNAME.github.io/sanatana-dharma-qa/`

## How to Host on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (create an account if needed)
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository: `sanatana-dharma-qa`
4. Make it **Public**
5. Click "Create repository"

### Step 2: Upload the Files

**Method A: Using GitHub Website (Easiest)**

1. In your new repository, click "uploading an existing file"
2. Drag and drop the `index.html` file
3. Click "Commit changes"

**Method B: Using Git (If you know Git)**

```bash
git clone https://github.com/YOUR-USERNAME/sanatana-dharma-qa.git
cd sanatana-dharma-qa
# Copy index.html into this folder
git add index.html
git commit -m "Add Sanatana Dharma Q&A app"
git push
```

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings**
2. Scroll down to **Pages** (in the left sidebar)
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Step 4: Access Your App

Your app will be live at:
```
https://YOUR-USERNAME.github.io/sanatana-dharma-qa/
```

Replace `YOUR-USERNAME` with your actual GitHub username.

## Customization

You can easily customize the app by editing `index.html`:

### Change Colors
Find the `:root` section at the top of the `<style>` tag:
```css
:root {
    --saffron: #FF9933;
    --deep-red: #8B1538;
    --gold: #C9A961;
    /* ... change these values */
}
```

### Add More Questions
Find the `qaData` array in the JavaScript and add new objects:
```javascript
{
    question: "Your question here?",
    category: "Hinduism",
    answer: "Your answer here..."
}
```

### Change Fonts
Modify the Google Fonts link in the `<head>` section.

## Browser Compatibility

- ✅ Chrome (Desktop & Mobile)
- ✅ Safari (Desktop & Mobile)
- ✅ Firefox
- ✅ Edge
- ✅ iPhone/iPad (iOS)
- ✅ Android

## Content

Contains 20 thoughtfully answered questions covering:
- Hindu philosophy and concepts
- Rituals and practices
- Marriage and relationships
- Women in Hinduism
- Modern perspectives
- Environment and sustainability
- Language and culture

## License

Feel free to use, modify, and share this application.

## Support

If you encounter any issues:
1. Make sure the file is named exactly `index.html`
2. Check that GitHub Pages is enabled in repository settings
3. Clear your browser cache
4. Wait a few minutes after enabling GitHub Pages

## Screenshots

The app features:
- Beautiful gradient cover page
- Category filter buttons
- Card-based Q&A layout
- Smooth scrolling
- Mobile-optimized design

---

Created with ❤️ for sharing Sanatana Dharma wisdom with youth
