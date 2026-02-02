# Minimal Academic Homepage - TODO

This is a minimal academic homepage created for Jiahao Liu.

## Items to Complete

### 1. Author Profile Photo
The current `images/profile.png` is a placeholder. To use your own photo:
- Replace `images/profile.png` with your actual photo
- Recommended size: 300x300px or larger
- File format: PNG or JPG

**Note:** The provided PDF files (`files/paper1.pdf`, `files/paper2.pdf`, `files/paper3.pdf`) do not contain author photos, so automatic extraction was not possible.

### 2. Publication PDF Files
The following PDF files are now available in the `files/` directory:

| Publication | Expected Filename | Status |
|------------|------------------|--------|
| Universally Composable Subversion-Resilient Authenticated Key Exchange (ASIACRYPT 2025) | `files/asiacrypt2025.pdf` | ✅ Added |
| srTLS: Secure TLS Handshake on Corrupted Machines (IEEE TDSC 2024) | `files/srtls-tdsc2024.pdf` | ✅ Added |

### 3. Contact Information
Email address has been updated to anti-spam format:
- `_config.yml` (line 20): `liujiahao14 at nudt dot edu dot cn` ✅
- `_pages/about.md` (line 42): `liujiahao14 at nudt dot edu dot cn` ✅

### 4. Research Details
Update research description and interests in `_pages/about.md` as needed.

### 5. Social/Profile Links
Update or add your profile links in `_config.yml`:
- Google Scholar URL
- ORCID (if available)
- ResearchGate (if available)
- LinkedIn (if desired)

## Deploy to GitHub Pages

Run the following commands in `crvpt0.github.io` directory:

```bash
git add .
git commit -m "style: refactor homepage to minimal academic theme"
git push
```

After pushing, your site will be deployed automatically to: https://crvpt0.github.io

## Local Preview

To preview the site locally:
```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000 in your browser.

## Design Notes

This is a minimal academic homepage with:
- Black/white/gray color scheme
- Clean typography with ample whitespace
- Responsive design for mobile and desktop
- Essential sections: About, Research, Publications, Contact
- Minimal navigation menu
- Author profile sidebar with photo
