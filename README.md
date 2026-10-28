# PROTOCOL by Mag
Static website and installable app (PWA). No build step.

## Put it on GitHub
1. Create a new repository on github.com named `protocol-by-mag`.
2. In this folder run:
   git init && git add . && git commit -m "Launch site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/protocol-by-mag.git
   git push -u origin main

## Host on Vercel
1. Sign in at vercel.com with GitHub, choose Add New > Project, import `protocol-by-mag`.
2. Framework Preset: Other. Leave build and output settings empty. Click Deploy.
3. Every push to `main` redeploys automatically. Add your own domain under Project > Settings > Domains.

## Install as an app
Android/Chrome: open the live site, tap Install app. iPhone: Share > Add to Home Screen.
For a Play Store APK, enter the live URL at pwabuilder.com.
