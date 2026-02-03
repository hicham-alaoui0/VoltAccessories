# VoltAccessories - Premium Tech Shopify Theme

## Overview
VoltAccessories is a high-converting, Online Store 2.0 theme built for dropshipping tech accessories. It features a premium-minimal design, custom sections for trust and engagement, and a mobile-first architecture.

## Getting Started

### 1. Requirements
- Shopify Store
- Shopify CLI (optional, for local development)

### 2. Installation (ZIP Upload)
1. Download the `theme-tech-accessories-os2.zip` file.
2. Go to your Shopify Admin > **Online Store** > **Themes**.
3. Click **Add theme** > **Upload zip file**.
4. Select the file and click **Upload**.
5. Once uploaded, click **Customize** to configure your store.

### 3. Key Customizations

#### Colors & Typography
- Go to **Theme Settings** > **Colors** to adjust the 3 preset schemes (Light, Dark, Accent).
- Go to **Typography** to set your fonts.

#### Homepage Sections
- **Trust Bar**: Add the "Trust Bar" section. Add blocks for each icon/text pair. Paste SVG code for icons (inline SVG for performance).
- **Category Tiles**: Add "Category Tiles". Add blocks for each category (Image + Link).
- **Testimonials**: Add "Testimonials". Add blocks for reviews.

#### Product Page
- The product template includes **Tech Specs** and **Compatibility** tabs.
- To display unique content per product, use **Metafields**.

### 4. Metafields Setup
To fully utilize the product page features, create the following Product Metafields in Shopify Admin (> Settings > Custom Data > Products):
- `custom.tech_specs` (Rich Text)
- `custom.compatibility` (Rich Text)
- `custom.shipping_estimate` (Single Line Text)
- `custom.in_the_box` (Rich Text)

Connect these metafields to the respective blocks in the Theme Editor.

### 5. Local Development
To run this theme locally:
```bash
shopify theme dev --path ./VoltAccessories
```

## Credits
Built on top of Shopify Dawn (Open Source).
Customized for VoltAccessories.
