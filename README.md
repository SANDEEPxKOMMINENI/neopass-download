# NeoPass Extension Download Page

A simple, modern download page for distributing the NeoPass browser extension to college lab computers.

## 🚀 Quick Deployment Options

### Option 1: Netlify (Recommended)
1. Push this folder to a GitHub repository
2. Connect your GitHub repo to Netlify
3. Deploy automatically
4. Get a free `yoursite.netlify.app` URL

### Option 2: Vercel
1. Push to GitHub
2. Import project in Vercel
3. Deploy with one click

### Option 3: GitHub Pages
1. Push to GitHub
2. Enable GitHub Pages in repository settings
3. Use `yourusername.github.io/repository-name`

## 📁 File Structure
```
download-page/
├── index.html          # Main download page
├── netlify.toml        # Netlify configuration
└── README.md           # This file
```

## 🔧 Setup Instructions

### 1. Prepare Your Extension
First, create a ZIP file of your extension:
```bash
# Navigate to your extension folder
cd "d:\Extension Kosam Hosting\NeoPass v1.3.0\NeoPass-main"

# Create ZIP file (you can also do this manually)
# Windows: Right-click folder → Send to → Compressed folder
```

### 2. Upload Extension ZIP
Upload your `neopass-v1.3.0.zip` to:
- GitHub Releases (recommended)
- Or directly to your hosting service

### 3. Update Download Links
Edit `index.html` and replace:
```javascript
const downloadUrl = 'https://github.com/yourusername/neopass/releases/download/v1.3.0/neopass-v1.3.0.zip';
```

With your actual download URL.

### 4. Deploy
Choose one of the deployment options above.

## 🎯 Features of the Download Page

- **Modern, responsive design**
- **Mobile-friendly**
- **Clear installation instructions**
- **Multiple download options**
- **Educational use disclaimer**
- **Feature highlights**

## 🔗 College Lab Distribution

Once deployed, students can:
1. Visit your hosted URL
2. Download the extension ZIP
3. Follow the installation instructions
4. Load the unpacked extension in Chrome

## 🛠️ Customization

You can customize:
- Colors and styling in the CSS
- Download URLs in the JavaScript
- Content and features list
- Add more download mirrors

## 📱 Example URLs After Deployment

- Netlify: `https://neopass-download.netlify.app`
- Vercel: `https://neopass-download.vercel.app`
- GitHub Pages: `https://yourusername.github.io/neopass-download`

## 🔒 Security Considerations

- HTTPS enforced for secure downloads
- Content Security Headers included
- Safe file download handling
- No server-side processing needed

---

**Note**: Remember to keep your extension updated and maintain the download links!
