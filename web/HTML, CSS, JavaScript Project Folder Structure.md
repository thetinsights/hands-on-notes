A well-organized folder structure improves code readability, maintainability, and scalability. Below is a recommended structure for a vanilla frontend project.

```plaintext
html-css-js-project/
│
├── 📁 assets/               # All static assets
│   ├── 📁 css/              # Stylesheets
│   │   └── style.css
│   │
│   ├── 📁 js/               # JavaScript files
│   │   ├── main.js
│   │   └── utils.js
│   │
│   ├── 📁 images/           # Images (PNG, JPG, SVG, etc.)
│   │   └── logo.png
│   │
│   └── 📁 fonts/            # Custom fonts
│       └── Inter.woff2
│
├── 📁 pages/                # Additional HTML pages (optional)
│   ├── about.html
│   └── contact.html
│
├── 📄 index.html            # Main HTML entry point
├── 📄 README.md             # Project documentation
├── 📄 .gitignore            # Ignore node_modules, etc. (if version-controlled)
└── 📄 LICENSE               # Optional license file

```

## Folder & File Descriptions

| Folder/File      | Purpose                                               |
| ---------------- | ----------------------------------------------------- |
| `assets/css/`    | All your global or modular CSS files go here          |
| `assets/js/`     | JavaScript files, modules, scripts                    |
| `assets/images/` | Logos, icons, illustrations                           |
| `assets/fonts/`  | Web fonts (WOFF, WOFF2, TTF)                          |
| `pages/`         | Optional sub-pages like `about.html`, `services.html` |
| `index.html`     | Main homepage                                         |
| `README.md`      | Project intro, setup, and usage instructions          |
| `.gitignore`     | Ignore unnecessary files in Git (if applicable)       |

## Tips

- Use **semantic and meaningful names** for files and folders.

- Keep styles, scripts, and assets **modular and reusable**.

- Group similar types of files together.

- Use a **version control system** (e.g., Git) and include a `.gitignore`.
