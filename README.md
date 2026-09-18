<div align="center">

# 📌 PIN88

**Your bookmarks, kept where they belong — on your device, and nowhere else.**

</div>

---

## 👋 Welcome

Every bookmark manager I've ever used made me create an account. Then it wanted my email. Then it wanted to know which folders I wanted to *share* with a *team*. Then it wanted a monthly subscription for the privilege of saving a URL. Somewhere along the way, "bookmark" stopped meaning "a link I want to keep" and started meaning "a data point in someone else's product."

PIN88 does none of that.

It's a bookmark manager that lives entirely in your browser. Your links, your folders, your icons, your preferences — all stored on your own device, in a way that survives refreshes but never leaves your machine. There is no account to create. No sync to opt out of. No privacy policy to read, because there is no server collecting anything.

What it *does* have is a personality. The design is called **Neo-Brutalism** — thick black borders, hard drop shadows, chunky buttons that press down when you tap them, purple and lime and pink and blue accents sitting on a warm off-white canvas. It looks like software with opinions. It looks like something you'd want to open every day.

Open it, and you'll see: a search bar, folders across the top, a grid of bookmarks with their favicons, and a small floating dock at the bottom with five buttons. That's the whole interface. That's the whole tool.

---

## 📸 Look Inside

<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/PIN88-MC88/raw/main/images/preview-1.png" alt="The PIN88 bookmark grid" width="100%" />
  <br />
  <sub><b>① The bookmark grid</b></sub>
</div>

<br />
<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/PIN88-MC88/raw/main/images/preview-2.png" alt="Adding a new bookmark" width="100%" />
  <br />
  <sub><b>② Adding a bookmark</b></sub>
</div>

<br />
<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/PIN88-MC88/raw/main/images/preview-3.png" alt="The bottom dock" width="100%" />
  <br />
  <sub><b>③ The bottom dock</b></sub>
</div>

---

## ✨ What you'll find

**A splash screen that sets the tone.**  
Ten seconds of loading — a PIN88 logo, a progress bar in lime green, a percentage counter ticking up in real time. Tap anywhere or press any key to skip it. The delay is intentional: it gives the page time to settle, and it announces that this is a piece of software with a personality, not a website that loads instantly and forgets you the moment you close the tab.

**Two themes, one identity.**  
The default is warm off-white with the full Neo-Brutalist palette. The alternative swaps the accents to a cooler, bluer family. Both keep the thick black borders, the hard shadows, and the chunky buttons. One button in the dock flips between them, and your choice is saved.

**A search bar that filters as you type.**  
Type anything — a site name, a domain, a fragment of a URL — and the grid narrows in real time. No search button, no "press Enter", no page reload. Just instant filtering, the way it should always have been.

**Folders, not tags, not hierarchies.**  
Every bookmark belongs to one folder. *General* exists by default; you add more whenever you want. Click a folder tab to filter the grid. The tab shows a live count of how many bookmarks live inside it. When you're done with a folder, it stays until you delete it — PIN88 doesn't try to guess what you meant.

**Favicons, fetched automatically.**  
When you add a bookmark, PIN88 pulls the site's favicon from Google's public favicon service. You don't have to paste an image URL. You don't have to upload anything. It just works.

**A custom image, if you want one.**  
Don't like the auto-fetched favicon? Upload your own. PIN88 resizes it to 128 pixels, compresses it to JPEG, and stores it inline with the bookmark. The whole thing — image and all — sits in your browser's local storage. No CDN, no image host, no external request ever.

**Edit and delete without leaving the grid.**  
Hover over any bookmark and two small buttons appear in the top-right corner: **edit** and **delete**. Edit reopens the same modal you used to create it, with everything pre-filled. Delete asks once, then removes it. That's the whole interaction.

**A floating dock with five buttons.**  
At the bottom of the screen, always visible, a small toolbar with: **Import**, **Share**, **Add**, **Theme**, **Export**. Each one is a different color, each one does exactly one thing, and each one is reachable with a thumb on a phone. This is the entire control surface of the app.

**Share a folder with one file.**  
Open a folder, tap **Share**, and PIN88 builds a small JSON file with every bookmark in that folder — URLs, titles, custom images, everything. Download it, send it to anyone, and they can import it into their own PIN88 with one tap. No account, no invitation, no shared workspace. Just a file.

**Import and export everything.**  
The **Export** button creates a full backup of your bookmarks and folders. **Import** accepts both shared folders and full backups, merges them intelligently, and skips duplicates so you never end up with the same link twice.

**Built as a PWA from day one.**  
PIN88 registers a service worker the moment it loads. Install it to your home screen, and it behaves like a real app — same interface, same speed, works offline. Your data stays on your device, and the app stays with you even when the network doesn't.

---

## 🧭 How it works

**1. Open it.**  
One HTML file. The splash screen runs for a few seconds, and then the grid appears. Everything else is ready.

**2. Add your first bookmark.**  
Tap the **+** button in the dock. Enter a URL, and the title fills in automatically from the domain. Pick a folder. If you want a custom image, upload one — otherwise PIN88 uses the site's favicon. Tap **Save**.

**3. Create folders as you go.**  
Tap **+ Folder** at the end of the folder tabs. Give it a name. It appears immediately. You can add bookmarks to it right away, or move existing ones by editing them.

**4. Search whenever you have too many.**  
Type in the search bar. The grid filters as you type. Clear it to see everything again.

**5. Organize without fear.**  
Edit a bookmark to change its folder, its title, its URL, or its icon. Delete one and it's gone. Everything happens immediately — no "save changes" step, no confirmation dialog for anything except deletion.

**6. Share a folder, or back everything up.**  
Tap **Share** to download a folder as a small JSON file you can send to anyone. Tap **Export** to download a full backup. Tap **Import** to load either one back in.

**7. Switch themes whenever.**  
The pink button in the dock flips between the two color palettes. Your choice is remembered.

That's the whole app. No settings menu, no account, no sync, no surprises.

---

## 🛠️ A few small helps

**"Where is my data stored?"**  
Entirely in your browser's `localStorage`, on your own device. Nothing is uploaded. Nothing is synced. If you clear your browser data, the bookmarks are gone — so use the **Export** button to keep a backup somewhere safe, like a cloud drive or a USB stick.

**"Will my bookmarks appear on my other devices?"**  
Not automatically — and that's the point. PIN88 doesn't have an account system or cloud sync. If you want your bookmarks on another device, tap **Export**, move the file across (email, AirDrop, USB, anything), then tap **Import** on the other device. It takes thirty seconds, and it keeps your data completely under your control.

**"Can I share a folder with someone who doesn't use PIN88?"**  
Yes. The Share button downloads a small JSON file. Anyone can open it in a text editor and read the URLs. If they install PIN88, they can import it and get the whole folder — with titles, folders, and custom icons intact. If they don't want to install anything, they can still read the file.

**"The favicon for one of my sites looks wrong."**  
Google's favicon service is very good, but it doesn't know every site. When a favicon is missing or wrong, edit that bookmark and upload your own image. PIN88 will store it inline, and it will look right forever — even if the site never updates its icon.

**"How big can my custom images be?"**  
PIN88 resizes everything to 128×128 pixels and compresses it to JPEG before storing it. So even if you upload a 5 MB photo, the stored version is only a few kilobytes. You can add hundreds of bookmarks with custom images before hitting any storage limits.

**"What happens if my storage gets full?"**  
PIN88 will show a *"Storage full"* toast the moment a save fails. At that point, you can export a backup, then delete some bookmarks or custom images to free up space. The app will keep working with whatever fits.

**"Does the search find things inside folders?"**  
Yes. The search bar ignores the current folder filter — when you type something, PIN88 searches *all* your bookmarks, across every folder. Clear the search and the current folder filter comes back.

**"Why ten seconds of splash screen?"**  
It's a design choice, not a technical requirement. It gives the app a sense of *arriving* — the way a program booting on an old computer felt like an event rather than a loading spinner. If it bothers you, tap anywhere and it disappears instantly.

**"Can I install it as an app?"**  
Yes. Open it in Chrome or Safari and choose **Add to Home Screen**. PIN88 registers a service worker, caches its own files, and works offline once installed. Your bookmarks stay exactly where they are — on your device, in your browser, under your control.

**"What if I want to start over?"**  
Open **Settings** in the header, and tap **Delete All Data**. You'll be asked twice, because it's not reversible. If you want to keep a copy first, use **Export** before deleting.

---

<div align="center">

### 📞 A question, an idea, a bug?

[![Email](https://img.shields.io/badge/Email-mohamed005cheikh@gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mohamed005cheikh@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-+222_30_73_64_75-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/22230736475)
[![GitHub](https://img.shields.io/badge/GitHub-mohamed005cheikh--rgb-181717?style=flat-square&logo=github)](https://github.com/mohamed005cheikh-rgb)

<br />

*Your links. Your rules. No accounts.*

<sub>© 2026 Mohamed Cheikh — MC88</sub>

<br />
<br />

    ███    ███    ████████    ████████    ████████
    ████  ████   ███    ███  ███    ███  ███    ███
    ██ ████ ██   ███         ███    ███  ███    ███
    ██  ██  ██   ███          ████████    ████████
    ██      ██   ███         ███    ███  ███    ███
    ██      ██   ███    ███  ███    ███  ███    ███
    ██      ██    ████████    ████████    ████████

</div>
