# AGENT.md

## Project

Hydrolat e-commerce website.

## Stack

- PHP (SSR, no frameworks, each page = separate PHP file)
- MySQL
- Tailwind CSS (CDN)

## Structure

- /admin — admin panel
- /assets — css, js, images
- /includes — db.php, header.php, footer.php
- /uploads — product images

## Database

- categories
- effects
- products
- product_images
- product_effects
- reviews
- news
- orders
- order_items
- cart
- cart_items
- contact_messages

## Coding rules

- No frameworks
- Clean, minimal code
- All queries use PDO with prepared statements
- All pages include /includes/db.php
- Public pages include header.php and footer.php
- Admin pages have auth check at the top

## Design

- Style: eco (70%) + premium (30%)
- Primary color: green
- Minimal, clean UI
- Rounded corners, soft shadows, lots of whitespace
- Fully responsive (mobile first)
