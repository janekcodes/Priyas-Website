# Priya's Website

A little interactive story, built for a very good reason.

## What's in here
- `index.html` — the whole site (story pages, calendar, Spotify embed, everything)
- `photos/` — put your photos here (see below)

## Before you deploy
Search `index.html` for `EDIT ME` and fill in:
- The 4 chapter texts (how you met, an inside joke, a favorite memory, "something changed")
- The Spotify embed link (Share → Embed track on the song you want)
- The closing note

## Adding photos
Drop images into the `photos` folder named exactly:
```
chapter1.jpg
chapter2.jpg
chapter3.jpg
chapter4.jpg
celebration.jpg
```
Different extension (`.png`, `.jpeg`)? Just update that one `src="photos/..."` line in `index.html` to match.

## Deploying
1. Push this folder to a GitHub repo (see commands below)
2. Go to vercel.com → sign in with GitHub → Add New → Project → import this repo → Deploy
3. Send her the link Vercel gives you
