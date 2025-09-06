This is my Personal Portfolio.
# Portfolio_gun


🔹 Tech Stack:
Core: HTML, CSS (SASS), JavaScript
Bundler: Parcel
Styling: SCSS, Bootstrap 5
Libraries:
jQuery
Popper.js & @popperjs/core (tooltip & dropdown support)
Vanilla-tilt (3D tilt hover effect)

🔹 Setup Instructions:
# Clone the repository
git clone https://github.com/bansalgun31/Portfolio_gun.git
cd Portfolio_gun

# Install dependencies
npm install

# Start development server
npm start

# Build for production
npm run build

Parcel will start a local dev server and open the portfolio in your browser.


🔹 Challenges Faced & Solutions:
Here are some challenges likely relevant to your repo (you can confirm or tweak these):

1-Responsive Design Across Devices
Challenge: Making sure the portfolio looked clean on mobile, tablet, and desktop.
Solution: Used Bootstrap grid system & custom media queries in SCSS for fine-tuning.

2-Asset & Dependency Management
Challenge: Handling CSS, JS, and images without manually linking every file.
Solution: Implemented Parcel bundler, which auto-handles dependency graph & hot reloading.

3-Styling & Customization
Challenge: Modifying the base simplefolio template while keeping it maintainable.
Solution: Used SCSS partials for modular styling and Prettier for code formatting.

4-Animations / Interactivity
Challenge: Adding smooth hover/scroll effects without slowing performance.
Solution: Integrated Vanilla-tilt for lightweight 3D hover effect.
