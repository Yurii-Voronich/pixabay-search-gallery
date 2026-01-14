# Image Search App (Pixabay API)

This project is a web application for searching images by keyword using the
**Pixabay API**. Users can search for images, view them in a responsive gallery,
and load more results using pagination.

🔗 **Live Demo:** https://yurii-voronich.github.io/goit-js-hw-12/

---

## 🚀 Features

- 🔍 Image search by text query
- 🖼️ Gallery rendering of search results
- ⏳ Loader displayed during API requests
- ➕ Pagination with **Load more** button
- 📜 Smooth scrolling after loading new images
- ⚠️ Error and status notifications via **iziToast**

---

## 🧠 Application Logic

1. User enters a search query and submits the form
2. A request is sent to the Pixabay API
3. Images are rendered into the gallery
4. If more than one page is available, the **Load more** button appears
5. When the last page is reached:
   - the button is hidden
   - a notification is shown that no more images are available

---

## 🛠️ Technologies Used

- **JavaScript (ES Modules)**
- **Pixabay API**
- **Fetch API**
- **HTML5**
- **CSS3**
- **iziToast** — notifications
- **GitHub Pages** — deployment

---

## 📂 Project Structure

```
src/
├── js/
│   ├── pixabay-api.js       # Pixabay API requests
│   ├── render-functions.js # Gallery rendering, loader, buttons
│
├── css/
│   ├── styles.css           # Styles
│   ├── reset.css
│   ├── main.css
│
├── index.html
└── main.js                  # Main application logic
```

---

## ⚠️ Error Handling

- Empty input → error notification
- No search results → user is notified
- Last page reached → button hidden and notification shown

---

## 📦 Run Locally

```bash
git clone https://github.com/yurii-voronich/goit-js-hw-12.git
cd goit-js-hw-12
npm install
npm run dev
```

---
