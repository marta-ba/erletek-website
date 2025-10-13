
# 🧭 Guide to Reusing the Code for ERLETEK-WEBSITE

## 📁 General Structure
The project is organized into two main folders:
html5up-solid-state/
 Contains the original HTML5UP template.
 This folder should remain unmodified — it serves as the base reference for layout and design.


webpage/
 This is the customized development version of the ErleTEK website.
 All edited and newly created files are located here. This is the folder you’ll continue working in.



## 🧩 Structure of webpage/
webpage/
│
├── assets/
│   ├── css/                → Custom stylesheets
│   │   ├── fontawesome-all.min.css
│   │   ├── main.css
│   │   ├── noscript.css
│   │   └── close.svg
│   ├── js/                 → JavaScript scripts
│   ├── sass/               → SASS source files (if used)
│   └── webfonts/           → Fonts and icons
│
├── images/                 → Website images
│
├── elements.html           → Components or reusable sections
├── generic.html            → Base template for subpages
├── index.html              → Main website page
│
├── LICENSE.txt             → License for the HTML5UP template
└── README.txt              → Basic info about the template


## ⚙️ How to Reuse and Continue Development
Open the project in Visual Studio Code
 Copy or clone the entire ERLETEK-WEBSITE folder to your local environment and open it in VS Code.


Work inside the webpage/ folder
 This folder contains all custom edits and code.
 You don’t need to modify anything in html5up-solid-state/.


Edit the HTML files as needed


index.html: Main landing page.


generic.html: Template for additional pages.


elements.html: Reference page for reusable layout sections.


Update styles or scripts


Main CSS files are located in webpage/assets/css/.


Add any new custom styles in main.css or as separate .css files in the same folder.


Add images or resources


Place all images inside webpage/images/.


Make sure HTML file paths are correct (e.g., assets/images/image.jpg or ../images/image.jpg, depending on the file location).


Preview locally


Use the VS Code “Live Server” extension to preview the website and see updates in real time.


Maintenance


Avoid editing the template folder (html5up-solid-state).


If further development continues, document all major updates in a new CHANGELOG.md file.
