# ar0.eu Shortlinks

This is a simple static site configured for Cloudflare Pages to handle shortlink redirects.

## Structure

- `public/index.html`: The landing page for `ar0.eu`.
- `public/_redirects`: The configuration file for Cloudflare Pages redirects.

## How to Deploy on Cloudflare Pages

1. Log in to the Cloudflare Dashboard.
2. Go to **Workers & Pages** > **Create Application** > **Pages** > **Connect to Git**.
3. Select this repository.
4. In the **Build settings**:
   - **Framework preset**: None
   - **Build command**: (Leave empty)
   - **Build output directory**: `public`
5. Click **Save and Deploy**.
