# GamingUP27 Bitrate Calculator

Ek free, stylish, gaming-themed bitrate calculator jo upload speed se streaming ke liye best bitrate suggest karta hai (OBS, Twitch, YouTube Live, Facebook Gaming, Kick ke liye).

## GitHub par host kaise karein (GitHub Pages — free)

1. GitHub par ek naya repository banao, e.g. `bitrate-calculator`.
2. Is folder ki teeno files (`index.html`, `robots.txt`, `sitemap.xml`) us repository me upload/push kar do (root me, kisi sub-folder me nahi).
3. Repository ke **Settings → Pages** me jao.
4. **Branch** me `main` select karo aur folder `/ (root)` rakho, phir **Save** karo.
5. Kuch minute baad tumhara tool is link par live ho jayega:
   `https://<your-github-username>.github.io/bitrate-calculator/`

## SEO ke liye zaroori step

- `index.html` ke andar jo URL abhi `https://gamingup27.github.io/bitrate-calculator/` likha hai, use apne asli GitHub Pages URL se replace kar dena (agar username ya repo name alag ho) — ye teen jagah hai: `canonical` link, Open Graph tags, aur JSON-LD schema.
- `sitemap.xml` aur `robots.txt` me bhi wahi URL update kar dena.
- Google Search Console me sitemap submit karne se indexing fast ho jayegi.

## Customize

- Colors, fonts aur layout `index.html` ke `<style>` section me hai.
- Calculator ka logic (formula, platform caps) `<script>` section ke end me hai — yahan se aasani se bitrate formula ya platform limits change kar sakte ho.
