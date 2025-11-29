# Autocrat Ventures GST Website

## File Structure
```
/
├── index.html          (Main webpage)
├── styles.css          (Styling file)
├── assets/
│   └── logo.svg        (Company logo)
└── README.md           (This file)
```

## Upload Instructions for GoDaddy

### Step 1: Access Your GoDaddy Account
1. Log in to your GoDaddy account
2. Go to "My Products" section
3. Find your domain and click "Manage"

### Step 2: Access File Manager or FTP
**Option A: Using GoDaddy File Manager (Easiest)**
1. In the domain management page, look for "File Manager" or "Hosting"
2. Click on "File Manager" or "cPanel"
3. Navigate to the `public_html` folder (or `www` folder)

**Option B: Using FTP Client**
- Use an FTP client like FileZilla
- Connect using your GoDaddy FTP credentials
- Navigate to `public_html` folder

### Step 3: Upload Files
1. Upload all files to the `public_html` folder:
   - `index.html`
   - `styles.css`
   - `assets` folder (with `logo.svg` inside)

2. Make sure the folder structure is maintained:
   ```
   public_html/
   ├── index.html
   ├── styles.css
   └── assets/
       └── logo.svg
   ```

### Step 4: Verify
1. Visit your domain in a web browser
2. The website should load automatically (index.html is the default page)

## Notes
- The mobile number placeholder can be updated in `index.html` when ready
- All files are ready to upload as-is
- The website is responsive and will work on all devices
- No additional configuration needed

## Customization
- To update contact information, edit `index.html`
- To change colors or styling, edit `styles.css`
- To replace the logo, replace `assets/logo.svg` with your new logo file

