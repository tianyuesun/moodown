# MoodOwn

An interactive vision statement by Angela Sun, written as she returns to computer science.

It presents three proposed AI-native products (Family, Relationships, Providers), simulated mobile concept screens, a shared agent architecture, a map of current skills and gaps, and a two-year engineering roadmap. The site switches between English and Chinese.

## Structure

```
index.html      the page
css/style.css   all styles
js/main.js      scenes, concept screens, architecture, roadmap, language switch
images/og.jpg   preview image shown when the link is shared
favicon.svg     tab icon
404.html        shown for unknown addresses
vercel.json     Vercel settings (clean URLs, caching)
```

Plain HTML, CSS and JavaScript. There is no build step and nothing to install. The only outside request is to Google Fonts.

## Deploy on Vercel

1. Go to https://vercel.com/drop and sign in.
2. Drag this whole folder (or the zip) onto the page.
3. Choose a team, name the project, and select Deploy.

Each drop creates a new project. To keep one address across updates, connect the folder to a Git repository and import it in Vercel instead.

## Preview locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Notes

The product concepts are proposed and simulated. No AI model is connected, every person and scenario is synthetic, and nothing on the site offers therapy, diagnosis or medical advice.
