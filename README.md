# Romantic Surprise Website

One file (`index.html`), no build tools, no backend. It works on GitHub Pages and opens from a QR code.

## 1. Customize it (5 minutes)

Open `index.html` in any text editor and find the block marked **CUSTOMIZE HERE** near the start of the `<script>`. Edit only the text inside quotes.

| What to change | Setting |
|---|---|
| Heading and welcome text | `welcomeHeading`, `welcomeMessage` |
| Name used in the letter | `recipientName` (replaces `{name}`) |
| The 5 compliment cards | `compliments` |
| Extra compliments for "See More" | `moreCompliments` (shown one at a time, never repeated) |
| Cute meter score and caption | `meterScore`, `meterScoreText`, `meterCaption` |
| The secret letter | `letter` (greeting, paragraphs, signoff, from) |
| Character message | `characterMessage` |
| Button labels | `buttons` |
| Colors | `theme` |
| Music | `musicSrc` |

Tips:
- Keep each line wrapped in quotes and followed by a comma.
- To add a paragraph to the letter, add another quoted line inside `paragraphs`.
- Music is optional. Put an mp3 you have the right to use next to `index.html`, then set `musicSrc: "song.mp3"`. Leave it `""` and the button shows as disabled. Music never plays on its own.
- Open `index.html` by double-clicking to preview before publishing.

## 2. Publish on GitHub Pages

1. Create a free GitHub account and click **New repository**.
2. Name it (for example `surprise`), set it to **Public**, and create it.
3. Click **Add file → Upload files**, drag in `index.html` and `README.md`, then **Commit changes**.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then **Save**.
6. Wait 1 to 2 minutes and refresh the Pages screen. A green box shows your live address.

## 3. Copy the public URL

It looks like `https://YOUR-USERNAME.github.io/surprise/`. Copy it from the Pages screen, or from your browser's address bar after opening it. Make sure it starts with `https://`.

## 4. Make a QR code

1. Open a free QR generator (search "free QR code generator"; pick one that does not require an account for a basic URL code).
2. Choose the **URL** or **Website** type and paste your address.
3. Download the code as PNG (or SVG for printing).
4. Print it, put it in a card, or send it as an image.

## 5. Test the QR code

- Scan it with a different phone from the one you built it on, using the normal camera app.
- Confirm the page opens over `https://` with no warnings.
- Try it on both Wi-Fi and mobile data.
- Do a final run-through before giving it to anyone.

If you edit `index.html` later, re-upload it to the repository. The QR code does not change because the address stays the same.

## Final test checklist

**Mobile (Android and iPhone)**
- [ ] QR code opens the page from another phone
- [ ] "Open My Heart" plays the transition and shows the main page
- [ ] All 5 cards open with one tap
- [ ] "See More" adds a new message each tap and stops when finished
- [ ] Meter animates when scrolled into view
- [ ] Envelope opens, letter reads well, "Fold the letter" closes it
- [ ] Music button is disabled (or works, if you added a file)
- [ ] No sideways scrolling in portrait or landscape
- [ ] Copy link / share works
- [ ] Facebook and email icons open correctly

**Desktop (Windows and Mac)**
- [ ] Layout looks right when the window is resized
- [ ] Tab key reaches every button, with a visible focus ring
- [ ] Replay returns to the welcome screen and resets everything
- [ ] Back-to-top button appears after scrolling
- [ ] Browser console (F12) shows no errors

**Accessibility**
- [ ] With "Reduce motion" turned on in your system settings, floating hearts and animations are off and everything still works
