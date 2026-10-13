WEDDING STUDIO — GITHUB PAGES VERSION (NO FIREBASE)
===================================================

Is version mein Firebase ya database ki zaroorat nahi. Website GitHub Pages par static
HTML/CSS/JavaScript files se live ho sakti hai.

FILES
-----
index.html      Website ka main page
styles.css      Design aur mobile responsive styling
app.js          Products, categories, cart, invoice, admin demo, WhatsApp order handoff

DEMO ADMIN PASSWORD
-------------------
Studio@2026

IMPORTANT: Ye sirf frontend demo lock hai. Password source code mein hota hai aur ise secure
admin login nahi maana ja sakta. Sensitive customer data ke liye ise production security na samjhein.

GITHUB PAGES PAR LIVE KARNE KE STEPS
------------------------------------
1. ZIP extract karein.
2. GitHub par apni repository open karein (ya nayi repository banayein).
3. Is folder ke andar ki files upload karein — index.html, styles.css, app.js aur README-HINGLISH.txt.
   Dhyan: index.html repository ke root mein hona chahiye, kisi extra subfolder ke andar nahi.
4. Repository > Settings > Pages open karein.
5. Build and deployment mein "Deploy from a branch" select karein.
6. Branch: main, folder: /(root) select karke Save karein.
7. GitHub Pages ka diya hua URL open karein.

ADMIN MEIN SETUP
----------------
1. Website open karein aur Admin button dabayein.
2. Password: Studio@2026
3. Categories tab mein categories create karein. Active categories website menu mein dikhengi.
4. Listings & Inventory tab mein product name, price, stock, image URL, optional View Design link
   aur description add karein.
5. Website Customisation mein website name, logo initials, colour aur social links set karein.
6. WhatsApp number field mein country code ke saath digits daalein, example format: 919876543210.
   Plus sign, spaces aur dashes na daalein.
7. Settings se JSON backup export karke safe jagah rakhein.

ORDER KAISE MILEGA?
-------------------
- Customer checkout submit karega.
- Agar Admin > Website Customisation mein WhatsApp number configured hai, website WhatsApp chat
  ko order details ke saath kholegi. Customer ko WhatsApp mein Send dabana hoga.
- Is tarah order aapke WhatsApp par aa sakta hai bina Firebase/backend ke.
- Order list website ke usi browser mein bhi save hoti hai, lekin alag phone/browser par sync nahi hoti.
- Agar WhatsApp number set nahi hai, order sirf customer ke current browser mein save hoga.

LIMITATIONS — SEEDHI BAAT
------------------------
- GitHub Pages static hosting hai; ismein private database ya server-side admin login nahi.
- Categories/products browser ke localStorage mein save hote hain. Aapke phone par kiye changes
  customers ke doosre devices par automatically update nahi honge. Public catalog ko globally
  update karne ke liye code/data ko repository mein publish karna ya hosted data service chahiye.
- Admin password browser source se dekha/bypass kiya ja sakta hai. Real customer data ko protect
  karne ke liye is demo ko secure store admin ke roop mein use na karein.
- WhatsApp handoff ke liye customer ko WhatsApp mein Send press karna hoga.
- Online payment gateway connected nahi hai. Payment receive/verify hone ka claim nahi karna.
- Invoice screen order summary / print-to-PDF hai; ye tax-compliant GST invoice nahi hai.
- Product images ke liye publicly accessible image URL use karein.
- Local browser data clear ho sakta hai; backup export karte rahein.
