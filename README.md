# 📂Project Structure
my-blog/
├── public/
│   └── favicon.ico
├── src/
│   ├── assets/             # Images, fonts, etc.
│   ├── components/         # Reusable UI pieces
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   ├── PostCard.jsx    # Card preview of a blog post
│   │   └── ...             
│   ├── data/
│   │   └── posts.json      # Local post data (mock DB)
│   ├── pages/              # Route-level components
│   │   ├── Home.jsx
│   │   ├── About.jsx
│   │   ├── PostDetail.jsx  # Full single post
│   │   └── NotFound.jsx
│   ├── styles/
│   │   └── main.css        # Global CSS or Tailwind import
│   ├── App.jsx             # App entry point
│   ├── main.jsx            # ReactDOM render
│   └── router.jsx          # (Optional) Centralized routing
├── .gitignore
├── index.html
├── package.json
├── README.md
└── vite.config.js

