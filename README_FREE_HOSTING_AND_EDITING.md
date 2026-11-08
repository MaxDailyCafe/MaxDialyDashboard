# MAX DAILY — QR Code & Digital Hub Guide

## 1. What Is Included in This Package
- **`index.html`**: Your mobile-first **MAX DAILY Digital Hub Dashboard** containing:
  - **MAX DAILY Circular Gold-Rimmed Logo Seal**
  - **Subtitle**: `SPECIALTY COFFEE & BAKERY`
  - **Slogan**: `A DAILY DOSE OF POSITIVITY`
  - **Google Review Spotlight Card**: `4.9 ★★★★★` rating + direct **Rate Us on Google** link
  - **Websites & Digital Menu**: Official Website, built-in **Interactive Digital Menu Drawer** (Espresso, Signatures, Manual Brew, Frappe, and Bakery), and WhatsApp Order button
  - **Social Media Channels**: Instagram, TikTok, and Facebook
  - **Location & Directions Card**: Branch address, working hours, phone call button, Wi-Fi one-tap password copy, and **Open in Google Maps** button
  - **Built-in Live QR Studio & Link Customizer**: Tap **`QR & EDIT LINKS`** at the bottom of the screen to edit any URL, add new buttons anytime in the future, and export an updated `hub_config.json`.
- **`hub_config.json`**: Your single configuration file where all links, phone numbers, Wi-Fi password, and menu prices live.
- **`1_QR_Codes_Vector_And_PNG/`**:
  - `MAX_DAILY_QR_Cream_Light_4000px.png` & `.svg`
  - `MAX_DAILY_QR_Espresso_Dark_4000px.png` & `.svg`
  - `MAX_DAILY_QR_Transparent_Gold_4000px.png` & `.svg`
- **`2_Print_Ready_Table_And_Counter_Cards/`**:
  - `MAX_DAILY_Table_Tent_QR_Card_Print_Ready.png` & `.svg` (Luxury Arch Table Tent / Counter Stand ready for printing)

---

## 2. How to Publish for Free Forever ($0/month, Unlimited Scans)

### Option A: Netlify Drop (Fastest — Takes 30 Seconds)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop) and sign in (free).
2. Drag and drop this entire `QR_Brand_Hub_Dashboard` folder onto the page.
3. Under **Site Configuration → Change site name**, set your free site name to `maxdaily` (giving you `https://maxdaily.netlify.app`).

### Option B: GitHub Pages (`https://maxdaily.github.io/hub`)
1. Create a free GitHub account with username **`maxdaily`** at [https://github.com/signup](https://github.com/signup).
2. Create a new public repository named **`hub`**.
3. Upload `index.html` and `hub_config.json` to the repository and enable **Settings → Pages → Deploy from `main` branch**.
4. Your dashboard will be live forever at **`https://maxdaily.github.io/hub`** — which is the exact URL already encoded into the QR codes in `1_QR_Codes_Vector_And_PNG/`!

---

## 3. How to Add or Change Links Later (Without Re-Printing the QR Code)
Whenever you want to update your Instagram link, Google Maps link, add a new delivery platform, or adjust menu prices:
1. Open `hub_config.json` (or use the **`QR & EDIT LINKS`** button inside the dashboard and click **`Export hub_config.json`**).
2. Replace `hub_config.json` on your GitHub / Netlify host.
3. Every existing printed QR code on your cups, tables, and counter stands will immediately show the new links!
