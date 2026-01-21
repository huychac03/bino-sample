# bino.com.vn Landing Page

A beautiful liquid glass themed landing page for the bino.com.vn domain sales page.

## Deploy to Cloudflare Pages

### Option 1: Direct Upload

1. Go to [Cloudflare Pages](https://dash.cloudflare.com/)
2. Create a new project
3. Select "Upload assets" or "Direct Upload"
4. Upload the entire project folder
5. Click "Deploy"

### Option 2: Git Integration

1. Push this project to a Git repository (GitHub/GitLab)
2. In Cloudflare Pages, create a new project
3. Connect to your Git repository
4. Build settings:
   - **Build command**: Leave empty (static HTML)
   - **Build output directory**: `/`
5. Click "Deploy"

### Option 3: Wrangler CLI

```bash
# Install Wrangler
npm install -g wrangler

# Login to Cloudflare
wrangler login

# Deploy
cd bino-landing
wrangler pages publish . --project-name=bino-landing
```

## Customization

- **Primary color**: Change `--primary: #643DC4` in `assets/style.css`
- **Content**: Edit `index.html`
- **Email**: Update the mailto link in the CTA button

## Project Structure

```
bino-landing/
├── index.html          # Main HTML file
├── assets/
│   └── style.css      # Liquid glass theme styles
└── README.md          # This file
```
