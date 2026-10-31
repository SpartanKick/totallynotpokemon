WILDMOOR PACKS - how to share it with friends
=============================================

What this folder is
-------------------
A complete little website. Put it on any web host and you get a normal link
(like https://something.netlify.app) that you can send to friends.
Friends open the link and can "install" the app to their home screen.
It then works offline too.

Each person's collection is saved on their OWN device. Nothing is uploaded,
and there is no account. Use Library > Backup and restore to move a
collection to another phone.

Pick ONE of these ways to put it online (all free)
---------------------------------------------------
A) Netlify Drop (fastest, about 2 minutes)
   1. Open https://app.netlify.com/drop in your browser.
   2. Drag the whole "wildmoor-site" folder onto the page.
      (On a phone, use a computer if you can, or option B.)
   3. You get a link. Sign in if it asks, so the site is not deleted.
   4. Send the link to your friends.

B) GitHub Pages
   1. Make a free GitHub account and a new public repository.
   2. Upload every file from this folder (index.html, sw.js, the icons,
      manifest.webmanifest).
   3. In the repository: Settings > Pages > Deploy from a branch > main.
   4. After a minute your link is https://YOURNAME.github.io/REPOSITORY/

C) Cloudflare Pages
   1. Make a free Cloudflare account, open Workers & Pages > Create > Pages.
   2. Choose "Upload assets" and upload this folder.

Updating later
--------------
Upload the new files over the old ones. Friends get the new version the next
time they open the app (the app tells them to close and reopen it).

For your friends
----------------
- Android (Chrome): open the link, then menu > Install app (or Add to Home screen).
- iPhone (Safari): open the link, tap Share > Add to Home Screen.
- The app starts with an original made-up set called Wildmoor. To use other
  card sets they import their own data in the Library tab.
- Prices and card images load from public websites, so they need a connection.

Trading between friends
-----------------------
In the Binder tab, "Trade with a friend" lets two people swap duplicate cards
directly between their phones. They connect by scanning each other's QR codes
when they are together, or by sending short codes (for example over WhatsApp) when
they are apart. No account and no server of yours is needed. Scanning uses the phone's
built-in QR reader, or loads a small reader from the internet on iPhone.
The phones use free public STUN helper servers (Google, Cloudflare) only to find
each other. Cards never pass through them. If two phones on mobile data cannot
connect, try both on the same Wi-Fi. Trades run on trust, so only trade with friends.

A note on card images and names
-------------------------------
This app contains no Pokemon artwork, names or card data. Pokemon and its
cards belong to their owners. Please keep sharing to friends, do not publish
a ready-made library of someone else's card images, and do not sell it.

Just want to send one file?
---------------------------
Send wildmoor.html (not this folder). Friends open it in Chrome. It works,
but it cannot be installed and some phones will not remember the collection
between visits, so the hosted link above is better.
