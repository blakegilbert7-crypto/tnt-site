# T•N•T Threads & Bows website (mockup)

Open `index.html` in a browser, or drag this whole folder onto https://app.netlify.com/drop to put it online for free.

## Turning on real booking and order emails (about 10 minutes)
1. Make a free account at https://www.emailjs.com and connect the shop's Gmail under **Email Services**. Copy the **Service ID**.
2. Under **Email Templates**, create a template with:
   - To email: `{{to_email}}`
   - Subject: `{{subject}}`
   - Reply-To: `{{reply_to}}`
   - Content (switch to the code editor): `{{{html_message}}}` (three braces, so the pink email design shows up)
   Copy the **Template ID**.
3. Copy your **Public Key** from Account settings.
4. On the website, open the footer link "Shop owner? Open your studio" → Settings, and fill in the notification email plus the three EmailJS values.

From then on every party request and order sends the pink notification email to that inbox, and Reply goes straight to the customer.

## Good to know
- Payments: Cash App ($KearaLove24) and Venmo QR codes are the shop's real ones. Customers pay, add the order number as the note, and the owner marks the order paid in the studio.
- Apple Pay needs a card processor (Square or Stripe). The checkout already has a "coming soon" spot for it.
- This mockup saves products, prices and orders in the browser. A live shop needs a small backend or a platform (for example Square Online or Shopify) so changes show for every customer.
