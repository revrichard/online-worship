# Weekly Worship Slides

This is a simple, web-based worship presentation platform built using [Reveal.js](https://revealjs.com/). It is designed to support weekly services, whether in person, online, or for self-guided worship at home.

## Features

- Lightweight and responsive HTML presentation
- Slides written in Markdown for ease of editing
- Support for embedded video (YouTube, Vimeo, Dropbox)
- Optional integration with Google Slides for non-technical contributors
- Can be hosted for free via GitHub Pages

## Getting Started

1. **Clone or fork this repository**
2. **Edit `index.html`** to add or modify slides
   - You can write slides directly in HTML
   - Or use Markdown with the `data-markdown` attribute
3. **To embed a Google Slides presentation**:
   - Open your Google Slides deck
   - Click **File → Share → Publish to web**
   - Choose the **Embed** tab
   - Publish it and copy the iframe code
   - Paste the iframe into a new `<section>` inside the `index.html`

## Adding Video
You can embed video from platforms like YouTube or Vimeo, or host your own.

Example YouTube (with no ads):
```html
<iframe src="https://www.youtube-nocookie.com/embed/VIDEO_ID" allowfullscreen></iframe>
```

## Hosting
This site can be published using GitHub Pages:

1. Go to **Settings → Pages** in your repository
2. Choose the `main` branch and `/ (root)` folder
3. Save — your worship site will be live at `https://yourusername.github.io/repository-name`

## Contributing

To make it easier for others to contribute (e.g., service leaders):
- Encourage them to use Google Slides
- Ask them to send you the **published link or iframe embed code**
- Add their content to the site manually, or use a form system if needed

## License
This project is open source and available under the MIT License.

---

Let this be a space for spiritual reflection, participation, and peace — wherever people are.

---

*Created and maintained by Richard Hall

