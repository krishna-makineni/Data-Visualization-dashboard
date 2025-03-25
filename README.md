 Data-Visualization-dashboard
 This Data Visualization Dashboard is a responsive, interactive web application built using HTML, CSS, and JavaScript with Plotly.js for dynamic charts and jsPDF for exporting data to PDF.

The dashboard includes:
✅ Multiple interactive charts (Line, Bar, Pie, and Scatter)
✅ Dark mode toggle for better accessibility
✅ Dropdown filter for selecting data (Daily, Weekly, Monthly)
✅ Export options (CSV and PDF)
✅ Smooth UI with animations and gradient themes

🔹 Code Breakdown
1. HTML Structure (<body> Section)
The dashboard is wrapped inside a <div class="dashboard"> container.

Header Section: Contains the title, dropdown filter, export buttons, and a dark mode switch.

Charts Grid: Uses a <div class="charts-grid"> to display multiple visualizations dynamically.

2. CSS Styling (<style> Section)
The design follows modern UI principles using CSS variables and transitions.

Key Features:
🎨 Dark Mode Support – Uses --bg-color, --text-color, and --card-bg for smooth theme switching.
🎨 Gradient Button Effects – Uses linear-gradient(45deg, var(--accent-color), var(--success-color)) for aesthetic buttons.
🎨 Responsive Design – Uses CSS Grid (grid-template-columns: repeat(2, 1fr)) to adapt layouts.
🎨 Custom Toggle Switch – Implements a theme switch with a sliding button using CSS :before pseudo-element.

3. JavaScript Functionality (<script> Section)
The dashboard's interactivity is powered by JavaScript.

