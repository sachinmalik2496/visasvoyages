# Visasvoyages

Static website for **Visasvoyages** — professional study visa and tourist visa assistance for global destinations.

**Live site:** [visasvoyages.com](https://visasvoyages.com)

## Pages

| Page | File |
|------|------|
| Home | `index.html` |
| About Us | `about.html` |
| Study Visa Services | `study-visa.html` |
| Tourist Visa Services | `tourist-visa.html` |
| Countries We Serve | `countries.html` |
| Contact | `contact.html` |

## Local Preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages** in your repository.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Click **Save**. The site will be published at `https://<username>.github.io/visasvoyages/`.

## Custom Domain (visasvoyages.com)

A `CNAME` file is included with `visasvoyages.com`. After enabling GitHub Pages:

1. In **Settings → Pages**, enter `visasvoyages.com` as the custom domain.
2. At your domain registrar, add these DNS records:

   | Type | Name | Value |
   |------|------|-------|
   | A | `@` | `185.199.108.153` |
   | A | `@` | `185.199.109.153` |
   | A | `@` | `185.199.110.153` |
   | A | `@` | `185.199.111.153` |
   | CNAME | `www` | `<username>.github.io` |

3. Enable **Enforce HTTPS** once DNS propagates.

## Contact

- **Phone:** +91 8427111747
- **Email:** visasvoyages@gmail.com
- **Office:** SCO-6, Sector 20-D, Chandigarh
