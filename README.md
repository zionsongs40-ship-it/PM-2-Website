# PM-2 Website

Official download landing page for PM-2.

## Deploy on Render

1. Sign in to [Render](https://render.com/).
2. Choose **New +** → **Static Site**.
3. Connect the GitHub repository `zionsongs40-ship-it/PM-2-Website`.
4. Use these settings:
   - **Branch:** `main`
   - **Root Directory:** leave blank
   - **Build Command:** leave blank
   - **Publish Directory:** `.`
5. Click **Create Static Site**.

Render will publish the site and automatically redeploy when you push changes to the connected branch.

## Publish the installer

The download buttons point to this GitHub Release asset URL:

`https://github.com/zionsongs40-ship-it/PM-2-Website/releases/latest/download/PM-2-Setup-1.0.1.exe`

Create a GitHub release and attach the installer using the exact filename **PM-2-Setup-1.0.1.exe**. Do not commit the installer binary into this repository.

## Current release details

- Product: PM-2
- Version: 1.0.1
- Platform: Windows 64-bit
- Installer: PM-2-Setup-1.0.1.exe
- Runtime: Microsoft Edge WebView2 (the setup bundle checks for it and can install it; internet may be required)
