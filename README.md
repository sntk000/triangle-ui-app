# triangle-ui-app

This is a simple web-based UI where users can tap triangles to change their colors.  
It is intended for use on touch devices such as smartphones and tablets.

## 📁 Project Structure

```pgsql
triangle-ui-app/
├── index.html
├── review.html
├── assets/
│   ├── css/
│   │   └── style.css
│   └── js/
│       ├── main.js
│       └── review.js
├── data/
│   └── sample.json
└── README.md
```

## 🛠️ Development Workflow

1. Edit `index.html` and `main.js` to implement the triangle tapping UI.
2. Add functionality to allow users to input their name and submit their result.
3. Implement `review.html` and `review.js` to load a submitted JSON and visualize it.
4. Optionally, integrate with Google Apps Script to send submitted data to Google Sheets.
5. Deploy using GitHub Pages (static hosting).

## ✅ Features (planned)

- Tap to change triangle colors
- Save/submit the configuration
- Load and review submitted results
- Name/ID-based tracking
- Optional: Google Sheets integration via Apps Script
