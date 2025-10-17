
# Free Website Starter (GitHub Pages)

A minimalist, responsive static site for **the.glow.nest** — 100% free to host.

## Quick Deploy (GitHub Pages)

1. Create a GitHub account (free) at github.com.
2. Make a **public** repository named **USERNAME.github.io** (replace USERNAME with your GitHub username).
3. Upload all files from this folder to the repo root (drag & drop on GitHub works).
4. Go to **Settings → Pages** and ensure **Source: Deploy from a branch**, **Branch: main / root**.
5. Your site will be live at **https://USERNAME.github.io** within a couple of minutes.

## Edit Your Details

- Open `index.html`, `about.html`, `content.html`, `teaching.html`, `links.html`, `contact.html` and replace text.
- Update social links in the footer in each file (search for TikTok/Instagram/Pinterest).
- Change the email link on `contact.html` (search for `mailto:`).
- Replace images in `assets/img` with your own.

## Optional: Free contact form (no signup)

Use **FormSubmit**:
```html
<form action="https://formsubmit.co/YOUR_EMAIL" method="POST">
  <input type="hidden" name="_captcha" value="false">
  <input type="email" name="email" required placeholder="Your email">
  <textarea name="message" required placeholder="Your message"></textarea>
  <button type="submit">Send</button>
</form>
```

## Free Alternatives

- Netlify or Cloudflare Pages (drag-and-drop deploys)
- Google Sites or WordPress.com (subdomain, simpler but less flexible)

## License

MIT — free to use, remix, and share.
