PDF Editor — GitHub Pages Version

This project is a client‑side PDF editor you can deploy 100% free on GitHub Pages. No backend is required.

✨ Features

Upload PDFs (click or drag‑and‑drop)

Multi‑page navigation

Text selection & inline editing

Highlighting

Shapes & signatures

Undo / redo history

Local autosave

Dark/light mode

Export edited PDF (flattened)

🚀 Deploy on GitHub Pages

Create a GitHub repo (public)

Add these files:

index.html

style.css

script.js

Push to GitHub

Go to Settings → Pages

Select Deploy from branch → main → / (root)

Save — your site will appear at:

https://<username>.github.io/<repo>/

🗂 Project Structure

PDF-Editor/
│ index.html
│ style.css
│ script.js
│ README.md
└── assets/
    └── icons/

🧩 How It Works

PDF rendering uses PDF.js

Editing canvas uses Fabric.js

Flattening uses PDF-LIB

Autosave uses localStorage

🛠 Build & Modify

You can update UI, animations, tools, or extend capabilities (OCR, annotations, vector tools) without server changes.

📄 License

Free to use and modify.

