# Will you be my Valentine? 💌

A single-page, no-install Valentine's ask. Fill in a short form, send the link (or the file) to someone special, and watch the **Yes** button grow every time they hesitate.

Everything runs in the browser. Nothing is uploaded to a server — your details live only in the link or the file you download.

## How it works

1. Open `valentine-fixed.html` in any browser.
2. Fill in the form and press **Create my link**.
3. Share the link, or download the self-contained HTML file.
4. They open it, press **No** a few times, then press **Yes**.

## The builder

| Field | Required | Notes |
|---|---|---|
| Their name | Yes | Shown in the headline |
| Your name | No | Signs the final message |
| Picture | No | Paste an image link, or upload a photo |
| Opening line | No | Shown under the headline |
| If they hesitate | No | One line per press of **No** |
| Message after yes | No | Shown on the final screen |

Tips:
- A **hosted image link** keeps the shareable link short.
- An **uploaded photo** is cropped to a square and shrunk to 240px so the link stays manageable. For uploads, the downloaded file is the most reliable way to share.

## The ask

Each time they press **No**:
- the button shows the next line from your list (and loops when it runs out), and
- the **Yes** button gets bigger and wider, until it takes over the whole row.

## The yes

Pressing **Yes** shows confetti, their photo, your message and your signature.

## Sharing options

| Option | Best for | Caveat |
|---|---|---|
| Shareable link | Quick sending in chat | Very long if you upload a photo |
| Downloaded HTML file | Attach, email or AirDrop | Recipient opens it in a browser |

> The link points to wherever you opened the page. If you opened it from your computer (`file://`), the link will only work on that computer — host the page online (for example with GitHub Pages), or send the downloaded file instead.

## Files

```
valentine-fixed.html   the whole app (HTML + CSS + JS)
README.md              this file
```

## Notes

- Works offline once the page is open, except for the bear GIF, which loads from the web and is hidden if it fails.
- Reduced-motion settings are respected (confetti and animations are turned off).
- Pinch-zoom is allowed for accessibility.
