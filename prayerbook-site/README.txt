PRAYER BOOK - HOSTING ON YOUR OWN SITE

1. Upload everything in this folder (index.html, manifest.webmanifest, sw.js,
   and the icons folder) to a GitHub repo or a folder on your site,
   e.g. qtchallenge.com/prayerbook/ . Keep the files together as they are.
2. On iPhone, open the address in Safari. A tip at the bottom shows how to
   add it: Share button > Add to Home Screen. The blue cross-and-book icon
   is used, and it opens full screen like an app.
3. On Android/Chrome and desktop Chrome/Edge, an Install option appears in
   the browser menu (or address bar).

Notes
- iPhone never installs a web app by itself; the person has to tap
  Add to Home Screen. The tip appears only in iPhone Safari, and only
  until it is installed or dismissed.
- On your own site, the prayer list is saved on that device, not in a
  Claude account. To move a list over, use My List > Export > Backup in
  the Claude version, then Restore in the hosted version.
- After you update index.html, change "prayerbook-v1" in sw.js to
  "prayerbook-v2" (and so on) so phones pick up the new version.
