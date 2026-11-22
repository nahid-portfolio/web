# Nahid Hasan | Hugo Portfolio

A responsive, dark-mode personal portfolio website built with Hugo. It uses a custom layout and CSS, so you do not need to install a theme or any extra packages.

## 1. Install Hugo

1. Visit the official Hugo installation guide: https://gohugo.io/installation/
2. Install **Hugo Extended** for your operating system.
3. Open Command Prompt, PowerShell, or a terminal and check the installation:

```bash
hugo version
```

If the command prints a Hugo version, installation is ready.

## 2. Run the website locally

1. Extract `nahid-hasan-portfolio.zip`.
2. Open a terminal in the extracted `nahid-hasan-portfolio` folder (the folder containing `config.toml`).
3. Run:

```bash
hugo server
```

4. Wait until Hugo says the server is available. The default local address is:

```text
http://localhost:1313/
```

## 3. Preview in a browser

Open Chrome, Firefox, Edge, or another browser and enter **http://localhost:1313/** in the address bar. Keep the terminal running while you preview the website. Press `Ctrl + C` in the terminal to stop the server.

Hugo's server supports live preview. When you edit a site file and save it, refresh the browser if it does not update automatically.

## 4. Build the website

To generate the production website files, run:

```bash
hugo
```

Hugo creates the generated website in the `public/` folder. You can submit the Hugo source project ZIP, and include `public/` too if your instructor specifically requests the generated site.

## 5. What to submit

Unless your instructor gave different instructions, submit:

- `nahid-hasan-portfolio.zip` (the complete Hugo project source).
- Optionally, a second ZIP of the generated `public/` folder if the portal asks for the built website.

Do not submit the `.git` folder or temporary editor files. Check your assignment instructions for the required file type and naming convention.

## Project structure

```text
nahid-hasan-portfolio/
├── config.toml
├── content/
│   └── _index.md
├── layouts/
│   ├── _default/
│   │   └── baseof.html
│   └── index.html
├── static/
│   ├── css/
│   │   └── main.css
│   └── js/
│       └── main.js
└── README.md
```

## Personal information used

- Name: Nahid Hasan
- Title: Computer Science & Engineering Student
- University: Daffodil International University
- Email: 252-15-830@diu.edu.bd
- Facebook: https://www.facebook.com/devnahid990
- Skills: C, C++, Java, HTML, CSS, JavaScript
- Project: Student Management System

The professional title is phrased as **Computer Science & Engineering Student** based on the information supplied. The Student Management System is listed without invented technical details. You can expand its description when you have details to add.

## Editing your details

Most profile information is in `config.toml`. The page content and section text are in `layouts/index.html`. Styling is in `static/css/main.css`, and the small mobile-navigation/scroll animation script is in `static/js/main.js`.

If you update the email or Facebook URL in `config.toml`, the contact links update automatically.
