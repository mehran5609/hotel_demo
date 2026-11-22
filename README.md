# The Grand Table — Hotel Ordering Demo

A responsive, static restaurant ordering demo suitable for a Vercel preview.

## Run locally
Open `index.html` in a browser, or run:
`python3 -m http.server 8000`
Then visit `http://localhost:8000`.

## Deploy to Vercel
1. Create a GitHub repository.
2. Upload `index.html` to the repository root.
3. In Vercel, choose **Add New → Project** and import the repository.
4. Framework Preset: **Other**.
5. Build Command: leave blank.
6. Output Directory: `.` (or leave the default if Vercel detects the static site).
7. Deploy.

## Demo flow
- Add menu items to the cart and place a test order.
- Click **Open staff demo dashboard** in the footer.
- The dashboard shows orders saved in this browser.
- Open the customer site and dashboard in separate tabs in the same browser to demonstrate updates.

## Important demo limitations
This is a front-end prototype only. Orders are stored in the current browser's `localStorage`. It does NOT send orders to hotel staff on another device, send WhatsApp/SMS/email notifications, process payments, or provide secure staff authentication. Those features require a backend (for example Supabase), server-side validation, access controls and a production deployment.

## Customization
Replace:
- `The Grand Table` with the hotel's name.
- Hero/menu photos and sample food names/prices.
- Opening hours, order types, address and contact details.
- Currency if needed.

Menu data and demo behavior are in the `<script>` section near the bottom of `index.html`.
