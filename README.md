🚀 Project Overview
A premium, highly interactive, and responsive web-based payment checkout gateway engineered to provide a visual-first e-commerce checkout loop. The application moves away from boring standard forms by blending modern frontend development practices with fluid user-experience design patterns, native asynchronous loaders, and hardware-accelerated background animations.

🛠️ Technical Architecture & Features
3D WebGL Visualization Layer: Integrates Three.js to construct a real-time, fixed-position background rendering canvas (#beamsCanvas). It features procedural coordinate mapping to animate dynamic structural meshes without blocking the main browser execution thread.

Advanced Theme Orchestration: Leverages standard CSS :root variables and custom HTML5 data-theme selectors to smoothly transition every UI component—such as layout shadows, inputs, text layers, and containers—between rich dark aesthetics and hyper-vibrant light modes.

Single-Page Application (SPA) Sub-Routing: Implements a modular routing module managed with client-side JavaScript transitions (.page { display: none; } and .active { display: block; }) to allow immediate switching between specific billing forms (Credit Card fields, UPI portals, Amazon/Apple Pay Express checkouts) without requiring costly page reloads.

Micro-interactions & Micro-Animations:

Infinite Travel Lighting: Employs advanced CSS @keyframes selectors (star-movement-top/bottom) to mask background border gradients, crafting continuous luminous paths traveling along layout cards.

Tactile Form Elements: Control inputs, choice grids, and submit nodes deploy forward pseudo-elements (::before/::after) creating shine flashes, fluid translation offsets, and directional movement relative to the mouse cursor.

Async Loading Pipeline: Includes a loading spinner modal (#loader) mimicking actual payment verification times before cleanly executing a scaled confirmation prompt (#successPage).

Fully Responsive Adaptive Layout: Crafted with comprehensive media break-points (1200px, 768px, and 480px) that instantly re-orient elements from a spacious multi-pane dashboard layout down to a tightly optimized, vertically stacked linear smartphone array.

🧮 Technology Stack Used
Core Languages: Semantic HTML5, Core CSS3 (Flexbox/Grid architecture), and ES6+ JavaScript.

Graphics Framework: Three.js (WebGL rendering context).

Styling Mechanics: CSS Custom variables, hardware-accelerated transitions, and custom backdrop-filters.
