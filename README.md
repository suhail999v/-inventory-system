# -inventory-system
📦 Inventory Management & Financial Analytics System
​A lightweight, modern web-based inventory management dashboard built with pure HTML, CSS, and vanilla modern JavaScript (ES6+). It demonstrates core programming concepts like data modeling, input validation, dynamic badge categorization, and higher-order array methods (forEach, map, filter).
​🚀 Live Demo
​Deployable instantly via GitHub Pages, Vercel, or Netlify.


​GitHub Pages URL: https://<your-username>.github.io/<your-repository-name>/


​✨ Features


​Interactive Product Ingestion:

​Add products via a standard inline form or trigger the original browser prompt workflow (prompt()).
​Full data validation: ensures valid names and non-zero positive numeric values.



​Dynamic Tier Categorization:


​Automated product badge assignment using conditional threshold logic and a clean switch structure:

​🟣 Premium: Price \ge $500
​🔵 Standard: Price \ge $100 and < $500
​🟢 Budget: Price < $100





​Real-Time Financial Analytics:

​Local Scope Calculations: Custom iterative function calculating total aggregate asset value.

​Budget Filtering (filter + map): Dynamically filters items under $200 and extracts their product identifiers.


​Capitalized Formatting (map): Generates standardized report strings formatted as NAME: $PRICE.




​Built-in Virtual Terminal:

​An on-screen console mirror displaying real-time execution steps, formatted logs, and error traces directly on the page without needing to open developer tools.



​🛠️ Tech Stack

​HTML5: Semantic document structure
​CSS3: Custom responsive styling with dark-mode palette and CSS variables

​JavaScript (Vanilla ES6+):


​Array manipulation (push, map, filter, forEach)

​Arrow functions & default parameters
​DOM manipulation and dynamic element creation



​📁 Project Structure
