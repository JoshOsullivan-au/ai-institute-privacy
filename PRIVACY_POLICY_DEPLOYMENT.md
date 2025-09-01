# Privacy Policy Deployment Guide

## Quick Hosting Options for Your Privacy Policy URL

### Option 1: GitHub Pages (Free & Easy)

1. **Create a GitHub repository** (e.g., `ai-institute-privacy`)
2. **Upload the files**:
   - `privacy_policy.html` → rename to `index.html`
   - `privacy_policy.md` (optional, for markdown version)
3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
4. **Your URL will be**: `https://yourusername.github.io/ai-institute-privacy/`

### Option 2: Netlify (Free & Professional)

1. **Go to [netlify.com](https://netlify.com)**
2. **Drag and drop** the `privacy_policy.html` file
3. **Your URL will be**: `https://random-name.netlify.app`
4. **Custom domain**: You can add a custom domain later

### Option 3: Vercel (Free & Fast)

1. **Go to [vercel.com](https://vercel.com)**
2. **Import from GitHub** or drag and drop
3. **Your URL will be**: `https://your-project.vercel.app`

### Option 4: Your Existing Website

If you have an existing website:
1. **Upload** `privacy_policy.html` to your web server
2. **Access via**: `https://yourdomain.com/privacy-policy.html`

## Custom GPT Integration

Once you have your privacy policy URL, add it to your Custom GPT:

1. **Go to your Custom GPT settings**
2. **Add Privacy Policy URL** in the configuration
3. **Use your hosted URL** (e.g., `https://yourusername.github.io/ai-institute-privacy/`)

## Recommended: GitHub Pages Setup

Here's the exact steps for GitHub Pages:

```bash
# 1. Create new repository on GitHub
# 2. Clone it locally
git clone https://github.com/yourusername/ai-institute-privacy.git
cd ai-institute-privacy

# 3. Copy your privacy policy
cp /path/to/privacy_policy.html index.html

# 4. Commit and push
git add index.html
git commit -m "Add privacy policy"
git push origin main

# 5. Enable GitHub Pages in repository settings
# 6. Your URL: https://yourusername.github.io/ai-institute-privacy/
```

## Custom Domain (Optional)

If you want a custom domain like `privacy.aiinstitute.com.au`:

1. **Buy a domain** from a registrar
2. **Add CNAME record** pointing to your GitHub Pages URL
3. **Configure custom domain** in GitHub Pages settings
4. **Your final URL**: `https://privacy.aiinstitute.com.au`

## Files Created

- `privacy_policy.html` - Web-ready HTML version
- `privacy_policy.md` - Markdown version
- `PRIVACY_POLICY_DEPLOYMENT.md` - This deployment guide

## Next Steps

1. **Choose a hosting option** (GitHub Pages recommended)
2. **Deploy your privacy policy**
3. **Get your URL**
4. **Add the URL to your Custom GPT configuration**
5. **Test the link** to ensure it works

Your privacy policy URL will be ready for your Custom GPT integration!
