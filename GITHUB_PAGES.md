# Publish your site free with GitHub Pages (no coding, all clicks)

Big picture: GitHub is a free cloud locker for files. "GitHub Pages" is a
switch that turns one folder in that locker into a live website. We'll upload
your files and flip the switch.

## Before you start
Unzip `jucelyn-portfolio.zip` on your computer. You should see:
    index.html        (the main page — must sit at the TOP)
    projects/         (5 detail pages)
    images/           (your photos)
Do NOT upload the zip itself — GitHub won't open it. Upload the files inside.

## Step 1 — Make a free GitHub account
Go to https://github.com  →  Sign up. (Free plan is all you need.)

## Step 2 — Create a "repository" (a labeled box for your files)
- Click the + (top right) → "New repository".
- Repository name: for the cleanest web address, name it EXACTLY:
      yourusername.github.io      (use your real GitHub username)
  Example: if your username is jucelyndesign →  jucelyndesign.github.io
- Set it to PUBLIC (free Pages needs public).
- Leave everything else unticked. Click "Create repository".

Why that name? A repo named "yourusername.github.io" gives you a clean link
like  https://yourusername.github.io  with nothing extra tacked on the end.

## Step 3 — Upload your files
- On the new repo page, click "uploading an existing file" (the blue link),
  or "Add file" → "Upload files".
- Open your unzipped `jucelyn-portfolio` folder, select EVERYTHING INSIDE it
  (index.html, the projects folder, the images folder) and drag them into the
  browser. The folders keep their shape automatically.
- IMPORTANT: index.html must land at the top level (not inside another folder).
- Scroll down, click "Commit changes" (that just means "save").

## Step 4 — Turn on Pages (flip the switch)
- In the repo, click "Settings" (top menu) → "Pages" (left menu).
- Under "Source", choose: Deploy from a branch.
- Branch: main    Folder: / (root)    → click Save.

## Step 5 — Get your link
Wait about 1–2 minutes, refresh the Pages settings page. It will show:
    "Your site is live at https://yourusername.github.io"
Click it. That's your published portfolio. Share it anywhere.

## Updating later
Go to the repo → "Add file" → "Upload files" → drag the changed file(s) in →
Commit. To add your photos later, upload them into the `images` folder the
same way. Changes go live in a minute or two.

## Two common trip-ups
- Blank page? index.html was probably uploaded inside a subfolder. It must be
  at the top level of the repo.
- Images not showing? The file name must match EXACTLY (all lowercase, .jpg)
  and live inside the `images` folder.
