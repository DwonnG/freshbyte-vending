# FreshByte Vending Website

A simple, professional landing page for FreshByte Vending.

## 🍕 Live Site

[freshbytefoods.com](https://freshbytefoods.com)

## 🛠️ Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Google Fonts (Poppins)
- No build step required

## 📁 File Structure

```
├── index.html                # Main landing page
├── css/
│   └── styles.css            # Custom styles
├── images/
│   ├── freshbyteslogo.png    # Logo
│   ├── freshbytesbanner.png  # Banner image
│   └── favicon.png           # Browser tab icon
└── README.md                 # This file
```

## 🚀 Deployment Options

### Option 1: GitHub Pages (Free)

1. Create a new GitHub repository
2. Push this code to the repo
3. Go to **Settings** → **Pages**
4. Select **Source**: Deploy from a branch
5. Select **Branch**: main, / (root)
6. Click **Save**
7. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 2: Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Click **Add new site** → **Import an existing project**
3. Connect your GitHub repo
4. Deploy settings: Leave defaults (no build command needed)
5. Click **Deploy**
6. Your site will be live instantly

### Option 3: Connect Custom Domain

After deploying to GitHub Pages or Netlify:

1. Add a `CNAME` file with: `freshbytefoods.com`
2. In your domain registrar (Porkbun), add DNS records:
   - For GitHub Pages:
     - Type: CNAME, Name: www, Value: `yourusername.github.io`
     - Type: A, Name: @, Value: `185.199.108.153` (GitHub's IP)
   - For Netlify:
     - Follow Netlify's custom domain instructions

## 🧪 Local Development

Just open `index.html` in your browser:

```bash
# macOS
open index.html

# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📝 Customization

### Colors (in index.html)

```javascript
colors: {
    'fresh-dark': '#2D3E36',    // Dark green
    'fresh-green': '#4CAF50',   // Primary green
    'fresh-light': '#8BC34A',   // Light green
    'fresh-orange': '#FF6B35',  // Accent orange
    'fresh-cream': '#FFF8F0',   // Background
}
```

### Content Updates

Edit the text directly in `index.html`. All content is in one file for simplicity.

## 📧 Contact Info

Update these in `index.html`:
- Email: `contact.freshbytevending@gmail.com`
- Phone: `(470) 238-8285`
- LinkedIn: `https://www.linkedin.com/company/freshbyte-vending`

## 📄 License

© 2025 FreshByte Vending. All rights reserved.

