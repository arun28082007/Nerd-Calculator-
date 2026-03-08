🧮 NerdCalc: Advanced Terminal Calculator
NerdCalc is a sleek, web-based, terminal-style calculator designed specifically for engineers, mathematicians, developers, and data nerds. It features a fully functional Read-Eval-Print Loop (REPL), variable memory, advanced mathematical parsing, and built-in interactive 2D graphing.
✨ Features
 * Terminal REPL Interface: A developer-friendly command-line aesthetic with command history (use Up and Down arrow keys to recall previous inputs).
 * Advanced Mathematics: Powered by Math.js, it supports complex numbers, matrices, cross products, derivatives, and algebraic simplification.
 * Variable & Function Memory: Define variables (e.g., mass = 5 kg) and custom functions (e.g., f(x, y) = x^2 + y) that persist throughout your session.
 * Unit Conversions: Natively handles scientific units (e.g., 5.08 cm to inch, c = 299792458 m/s).
 * Interactive 2D Graphing: Built-in plot() command powered by Plotly.js that renders responsive, interactive graphs.
 * Responsive Design: A split-pane view for desktop users and a mobile-friendly modal view for graphing on smaller screens.
🚀 Getting Started
NerdCalc is completely client-side and requires no build steps, servers, or dependencies to install.
 * Clone or download this repository.
 * Open the index.html file in any modern web browser (Chrome, Firefox, Safari, Edge).
 * Start calculating!
Note: You need an active internet connection to load the external libraries (Tailwind CSS, Math.js, Plotly.js, and FontAwesome).
📖 Quick Command Reference
Here are a few commands and expressions you can try directly in the terminal:
System Commands
 * help - Displays the quick reference guide in the terminal.
 * clear - Clears the terminal history.
Basic Math & Algebra
> sqrt(16) + 5^2
> x = 10 / 2
> simplify('2x + x')

Calculus & Functions
> f(x, y) = x^2 + y
> f(2, 3)
> derivative('x^2 + x', 'x')

Matrices & Complex Numbers
> det([-1, 2; 3, 1])
> cross([1, 1, 0], [0, 1, 1])
> complex('2 + 3i') * i

Units & Graphing
> 5.08 cm to inch
> sin(45 deg) ^ 2
> plot(sin(x) * x)

🛠️ Technologies Used
 * HTML5 / JavaScript (Vanilla) - Core logic and DOM manipulation.
 * Tailwind CSS - For rapid UI styling and responsive design.
 * Math.js - For advanced mathematical parsing, evaluation, and REPL state management.
 * Plotly.js - For rendering interactive, high-performance 2D charts.
 * Font Awesome - For UI iconography.
📄 License
This project is open-source and available under the MIT License. Feel free to fork, modify, and use it in your own projects!
