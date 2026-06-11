# Sam & Kate Wedding Website — Build Plan

## Stack
- **Hosting:** GitHub Pages (`sambtrmntai/samandkatewedding` → `samandkate.me`)
- **Data collection:** Google Forms → Google Sheets (RSVPs, contact details)
- **Photos:** Google Photos embed (official), Google Drive upload link (guests)
- **Updates/mailing list:** Mailchimp free tier (up to 500 contacts)
- **No backend required** — static HTML/CSS/JS only

---

## Pages

1. **Home** — names, date, location, hero image/countdown
2. **Our Story** — short timeline / how we met
3. **Details** — ceremony + reception info, schedule, dress code
4. **RSVP** — embedded Google Form (name, attendance, dietary, contact email)
5. **Seating** — viewable seating chart (image or embedded Google Sheet, updated closer to date)
6. **Photos** — embedded Google Photos album for official photos; link to guest upload folder
7. **Updates** — latest news / changelog for guests (edited manually as needed)
8. **Contact** — simple contact info or form

---

## Build Phases

### Phase 1 — Structure & Design (Week 1)
- [ ] Decide on colour palette and fonts (suggest: soft dusty rose + sage + cream, serif headings)
- [ ] Build shared layout: nav, header, footer
- [ ] Home page with hero, names, date, location, countdown timer
- [ ] Details page with ceremony/reception info
- [ ] Mobile-responsive layout throughout

### Phase 2 — Data Collection (Week 1–2)
- [ ] Create Google Form for RSVPs (fields: name, +1, attendance, dietary requirements, email)
- [ ] Embed RSVP form on RSVP page
- [ ] Set up Mailchimp account and embed signup form for updates
- [ ] Test form submissions end-to-end

### Phase 3 — Media (Week 2)
- [ ] Set up Google Photos shared album for official photos
- [ ] Create Google Drive folder with upload link for guest photos
- [ ] Build Photos page with both embedded album and guest upload button
- [ ] Add Our Story page with photos/timeline

### Phase 4 — Polish & Launch (Week 2)
- [ ] Seating plan page (placeholder until closer to date)
- [ ] Updates/announcements section on home page
- [ ] Check all pages on mobile
- [ ] Verify samandkate.me loads with HTTPS (should auto-resolve within 24hrs of DNS setup)
- [ ] Send URL to a few people to test

---

## Notes
- Repo: `~/samandkatewedding/` (local), `github.com/sambtrmntai/samandkatewedding` (remote)
- Domain purchased at Porkbun, DNS pointed at GitHub Pages IPs
- QR code already generated and sent to invitation maker — URL is locked as `https://samandkate.me`
- Google Forms responses go to a linked Google Sheet — share that sheet with Kate too
- Don't add any paid services — everything here is free
