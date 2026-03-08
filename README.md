Virtual Nuclear Physics Lab ☢️

A comprehensive, browser-based interactive simulation for conducting classic nuclear physics experiments. This project features a virtual Geiger-Müller (GM) counter apparatus, realistic real-time particle decay physics, and dynamic graphing capabilities.

Built entirely in Vanilla JavaScript and HTML with Tailwind CSS, this simulation requires no backend, no build steps, and no installations to run.

🔬 Supported Experiments

This multipurpose lab simulator includes built-in manuals and dynamic controls for four fundamental nuclear physics experiments:

GM Tube Plateau Characteristics: Vary the operating voltage (300V - 1000V) to map the characteristic curve of a GM tube, identify the avalanche threshold, and find the optimal operating plateau.

Inverse Square Law: Adjust the source-detector distance to verify that radiation intensity is inversely proportional to the square of the distance ($I \propto 1/d^2$).

Absorption & End-Point Energy: Insert varying thicknesses of Aluminum absorbers between a Beta source (like Tl-204 or Sr-90) and the detector to find the "Range" and calculate the end-point energy of the beta particles.

Radioactive Half-Life: Track the real-time exponential decay of a simulated Barium-137m source ($T_{1/2} \approx 2.55$ mins). Uses a continuous global lab clock to plot a realistic decay curve.

✨ Key Features

Realistic Physics Engine: Particle counting is simulated in real-time (every 100ms) using Knuth's Poisson distribution algorithm to accurately model the statistical randomness of radioactive decay.

Integrated Lab Manuals: Each experiment mode comes with an embedded lab manual covering the theoretical background, experimental procedure, and key formulas.

Dynamic SVG Graphing: Automatically generates clean, real-time plots of your recorded data (e.g., Net CPS vs. Voltage, CPS vs. $1/d^2$, or CPS vs. Time) directly in the browser without external charting libraries.

Zero Dependencies: Fully self-contained in a single index.html file. Styling is handled via the Tailwind CSS CDN.

🚀 How to Run

Because this is a single-file Vanilla JS web app, getting it running is incredibly simple:

Clone or download this repository.

Double-click the index.html file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).

Select an experiment mode and start logging data!

Alternatively, you can host it instantly using GitHub Pages, Netlify, or Vercel by simply deploying the root directory.

🛠️ Tech Stack

HTML5 (Structure and Layout)

Vanilla JavaScript (ES6) (Physics logic, UI state, and SVG manipulation)

Tailwind CSS (via CDN) (Styling and responsive design)

📝 License

This project is open-source and available under the MIT License. Feel free to fork, modify, and use it for educational purposes!
