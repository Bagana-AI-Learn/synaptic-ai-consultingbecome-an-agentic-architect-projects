# GitHub Pages Setup Guide

## Current Repository
- **Organization**: `Bagana-AI-Learn`
- **Repository**: `synaptic-ai-consultingbecome-an-agentic-architect-projects`
- **Full URL**: `https://github.com/Bagana-AI-Learn/synaptic-ai-consultingbecome-an-agentic-architect-projects`

## Expected GitHub Pages URL

For organization repositories, the GitHub Pages URL format is:
```
https://bagana-ai-learn.github.io/synaptic-ai-consultingbecome-an-agentic-architect-projects/
```

**Note**: Organization names in GitHub Pages URLs are converted to lowercase.

## Steps to Enable GitHub Pages

1. **Go to Repository Settings**
   - Navigate to: `https://github.com/Bagana-AI-Learn/synaptic-ai-consultingbecome-an-agentic-architect-projects/settings`

2. **Enable GitHub Pages**
   - Scroll down to "Pages" section in the left sidebar
   - Under "Source", select:
     - **Branch**: `main`
     - **Folder**: `/ (root)`
   - Click "Save"

3. **Wait for Deployment**
   - GitHub Pages typically takes 1-2 minutes to deploy
   - You'll see a green checkmark when deployment is successful
   - The site will be available at the URL shown

4. **Verify Files Are Present**
   - Ensure `index.html` is in the root directory ✅
   - Ensure `projects.json` is in the root directory ✅
   - Ensure `projects/feb26-bagana-ai-louis-therhansen/` folder exists ✅

## Troubleshooting

### If the page shows 404:
1. Check that GitHub Pages is enabled in Settings → Pages
2. Verify the branch is set to `main`
3. Wait a few minutes for deployment to complete
4. Try accessing: `https://bagana-ai-learn.github.io/synaptic-ai-consultingbecome-an-agentic-architect-projects/` (without index.html)

### If the page loads but gallery is empty:
1. Open browser Developer Tools (F12)
2. Check Console for JavaScript errors
3. Check Network tab to see if `projects.json` is loading (should return 200 status)
4. Verify the path to `projects.json` in `index.html` line 270: `const res = await fetch('projects.json');`

### Alternative URL Format
If the organization URL doesn't work, try:
- `https://bagana-ai-learn.github.io/synaptic-ai-consultingbecome-an-agentic-architect-projects/index.html`
- Or check the actual URL shown in Settings → Pages after enabling

## Current File Structure
```
synaptic-ai-consultingbecome-an-agentic-architect-projects/
├── index.html                    ✅ Main gallery page
├── projects.json                 ✅ Projects data
├── README.md                     ✅ Documentation
├── PROJECT_SUMMARY.md            ✅ Project summary
└── projects/
    └── feb26-bagana-ai-louis-therhansen/
        ├── index.html            ✅ Project showcase page
        ├── hero.png              ✅ Hero image
        ├── screen-1.png          ✅ Screenshot 1
        ├── screen-2.png          ✅ Screenshot 2
        ├── screen-3.png          ✅ Screenshot 3
        ├── screen-4.png          ✅ Screenshot 4
        └── screen-5.png          ✅ Screenshot 5
```

## Verification Checklist
- [ ] GitHub Pages enabled in repository settings
- [ ] Source branch set to `main`
- [ ] All files committed and pushed to `main` branch
- [ ] Deployment shows green checkmark in Settings → Pages
- [ ] Can access the site at the GitHub Pages URL
- [ ] Gallery displays BAGANA AI card
- [ ] Clicking card opens detail page correctly
- [ ] All screenshots load on detail page
