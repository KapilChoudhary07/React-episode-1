📘 React Without Build Tools (CDN) – Example Project

This project demonstrates how to use React and ReactDOM directly in an HTML file using CDN links, without using bundlers like Webpack, Parcel, or Vite.

📄 index.html

The index.html file contains:

CDN links for React and ReactDOM

A <div id="root"></div> container where React renders UI

External JS file included (App.js)

Basic HTML content above and below the React root

🎨 App.js

This file contains React code using React.createElement to build nested elements:

A parent div

Two child divs (child and child2)

Inside them: <h1>, <h2>, <h3>, <h4> elements

Rendering using:

const root = ReactDOM.createRoot(document.getElementById("root")); root.render(parent);

🚀 How to Run the Project

Download this project folder.

Open the folder.

Double-click index.html → it will open in your browser.

React will render inside the <div id="root">.

💡 What You Learned

✔ How to use React without installation ✔ How to add React using CDN links ✔ How to render nested elements with React.createElement ✔ How React renders only inside the root div

📷 Output Overview

You will see normal HTML headings above and below the root

Inside the root, React renders:

h1 and h2 from child 1

h3 and h4 from child 2