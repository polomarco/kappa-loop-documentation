# GitBook Setup Guide for Kappa Loop

## Quick Start

Your documentation files are ready! Follow these steps to publish them on GitBook.

## Option 1: Direct Upload to GitBook (Easiest)

### 1. Create GitBook Account
1. Go to **https://gitbook.com**
2. Click "Sign up" (free for public docs)
3. Sign up with Google, GitHub, or email

### 2. Create a New Space
1. Click "New Space"
2. Name it: **"Kappa Loop User Guide"**
3. Choose: **"Documentation"** template
4. Click "Create"

### 3. Import Your Content

**Method A: Copy & Paste** (Quickest)
1. In GitBook, delete the default content
2. Open each `.md` file from this folder
3. Create matching pages in GitBook
4. Copy and paste the content

**Method B: GitHub Sync** (Recommended for Long-term)
1. Create a GitHub repository called `kappa-loop-docs`
2. Push all these files to the repo
3. In GitBook: Settings → Integrations → GitHub
4. Connect your repo
5. GitBook will auto-sync when you push changes

### 4. Configure Your Space

**Appearance**:
* Logo: Upload Kappa Loop logo
* Primary color: Use burgundy (#830915)
* Enable dark mode toggle

**Domain** (Optional but recommended):
* Settings → Domain → Custom domain
* Add: `docs.kappaloop.app` or `help.kappaloop.app`
* Update DNS with provided CNAME record

**Search**:
* Search is enabled by default
* Users can search all documentation

### 5. Publish
1. Click **"Publish"** (top right)
2. Choose visibility: **"Public"** (free)
3. Your docs are now live!

## Option 2: GitHub Integration (Best for Team)

### 1. Create GitHub Repo
```bash
cd ~/Documents/development/CleverLoops
git init kappa-loop-docs
cd kappa-loop-docs
git add .
git commit -m "Initial documentation"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/kappa-loop-docs.git
git push -u origin main
```

### 2. Connect to GitBook
1. In GitBook → Settings → Integrations
2. Click "GitHub"
3. Authorize GitBook
4. Select your `kappa-loop-docs` repository
5. Choose branch: `main`
6. Enable "Auto-sync"

### 3. Edit Workflow
Now you can:
* Edit `.md` files locally
* Commit and push to GitHub
* GitBook auto-updates your docs site

## Directory Structure

```
kappa-loop-docs/
├── README.md                    # Homepage
├── SUMMARY.md                   # Table of contents (navigation)
├── faq.md                       # FAQ page
├── getting-started/
│   └── creating-account.md
├── profile/
│   ├── README.md
│   └── deleting-account.md     # ⭐ Required for Google Play
├── announcements/
│   └── README.md
├── events/
├── settings/
├── troubleshooting/
└── policies/
```

## Important URLs for Google Play

After publishing, use these URLs in Google Play Console:

### Data Safety → Account Deletion URL
```
https://your-gitbook-url/profile/deleting-account
```

### Support URL
```
https://your-gitbook-url
```

### Privacy Policy URL
```
https://your-gitbook-url/policies/privacy
```

## Customization Tips

### Add Screenshots
1. Take screenshots in the app
2. Upload to GitBook (drag & drop into editor)
3. Add captions for context

### Add Videos
1. Upload videos to YouTube (unlisted)
2. Embed in GitBook using `/embed` command
3. Paste YouTube URL

### Add Code Snippets
Use triple backticks for code:
\`\`\`dart
// Example Dart code
void main() {
  print('Hello Kappa Loop!');
}
\`\`\`

### Add Callouts
```
{% hint style="info" %}
💡 Tip: This is a helpful tip for users!
{% endhint %}

{% hint style="warning" %}
⚠️ Warning: Important information
{% endhint %}

{% hint style="danger" %}
🚨 Critical: Requires immediate attention
{% endhint %}
```

## Analytics

GitBook includes basic analytics:
* Page views
* Popular searches
* User engagement

Access: Settings → Insights

## Team Collaboration

Invite team members:
1. Settings → Members
2. Add email addresses
3. Assign roles:
   * **Editor**: Can edit content
   * **Reader**: Can only view
   * **Admin**: Full access

## Maintenance

### Regular Updates
* Update screenshots when UI changes
* Add new features as they're released
* Keep FAQ updated with common questions
* Review analytics to improve content

### Content Review Schedule
* **Weekly**: Check for support tickets → Update FAQ
* **Monthly**: Review analytics → Improve popular pages
* **Quarterly**: Full content audit
* **On Release**: Update version numbers & new features

## Next Steps

1. ✅ Create GitBook account
2. ✅ Upload documentation
3. ✅ Configure custom domain
4. ✅ Add screenshots
5. ✅ Update Google Play Console URLs
6. ✅ Share with team

## Need Help?

* GitBook Docs: https://docs.gitbook.com
* GitBook Support: support@gitbook.com
* Video Tutorials: https://www.youtube.com/@GitBook

---

Good luck with your documentation! 🚀
