# Top Dairy Depot

Ordering website for Top Dairy Depot (Kampala, Uganda). Retailers and wholesalers pick their buyer type, build an order in UGX and send it by WhatsApp. Orders are also saved to Supabase.

- Single file site: `index.html` (photos embedded, no build step)
- Products and prices load from the Supabase `products` table (edit them in the Supabase Table Editor)
- Orders are saved to the Supabase `orders` table
- The key in `index.html` is a publishable key; Row Level Security only lets visitors read products and add orders

## Host free
Netlify: drag this folder onto app.netlify.com/drop
GitHub Pages: Settings > Pages > Deploy from branch > main / root
