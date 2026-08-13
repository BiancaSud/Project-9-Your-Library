# Your Library — Online Bookstore

An e-commerce bookstore interface with faceted filtering and a paginated product grid, built with HTML and CSS.

**Live site:** https://your-library-book-store.netlify.app/  /  
https://biancasud.github.io/Project-9-Your-Library/

![Your Library]
<img width="1893" height="944" alt="image" src="https://github.com/user-attachments/assets/765ad188-04b4-4920-a7e9-567379a8a8f7" />
<img width="1893" height="945" alt="image" src="https://github.com/user-attachments/assets/e931ee3f-b8e9-48b8-bd72-13b5a69141dc" />
<img width="403" height="825" alt="image" src="https://github.com/user-attachments/assets/8e7fe360-e701-4bc4-884c-44910f6a6443" />




## About

Your Library is a shop front for a book retailer. The focus of this project was the product-listing page: the layout pattern used by almost every real online store, with filters on one side and a grid of results on the other.

## Features

- **Faceted filter sidebar** covering five dimensions: category, publishing house, author, language and publication year, each with a "More" expander
- **Product grid** of 25+ books, each card showing cover, title, author and price
- **Category navigation bar** — bestseller, trending, discount pack, e-books, audio-books, accessories
- **Cart indicator** in the header
- **Pagination** across ten pages of results
- **Three-column footer** organized into website, help and about sections

## Built with

HTML5, CSS3. No frameworks or libraries.

## Running locally

```bash
git clone https://github.com/BiancaSud/Project-9-Your-Library.git
cd Project-9-Your-Library
```

Open `index.html` in a browser.

## What I focused on

Getting the two-column shop layout right — a fixed-width filter column beside a flexible product grid that reflows as the viewport changes. Keeping the product cards visually consistent across 25 items with different cover proportions and title lengths turned out to be the harder half of the job.

## Possible improvements

- Make the filters functional with JavaScript
- Working pagination and a real cart counter
- Responsive layout — the sidebar should collapse into a filter drawer on mobile
- Individual product pages
