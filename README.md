# FBD Sandbox

An interactive, real-time physics simulator for learning Newton's Laws through **Free Body Diagram visualization**. Create objects, apply forces, adjust environmental parameters, and watch physics unfold with live force vectors and formulas.

## Features

- **Object Creation**: Add boxes, balls, or heavy objects to the canvas
- **Interactive Modes**:
  - **Add Mode**: Place new objects on the canvas
  - **Push Mode**: Apply continuous forces to objects
  - **Throw Mode**: Launch objects with initial velocity
  - **Freeze Mode**: Pause all motion for analysis
- **Real-Time Force Visualization**: Display weight (Fg), normal force (N), applied force (Fa), friction (Ff), and net force vectors
- **Environmental Controls**:
  - Adjustable gravity (0.5–25 m/s²)
  - Configurable friction coefficient μ (0–1)
  - Bounciness/restitution coefficient e (0–0.95)
- **Object Properties**: Adjust mass (1–50 kg) of selected objects
- **Live Physics Formulas**: Display real-time calculations for the selected object
- **Impact Animations**: Visual feedback when objects collide or hit surfaces

## How to Use

1. **Open** `index.html` in a web browser
2. **Select an object type** (Box, Ball, or Heavy) from the sidebar
3. **Choose a mode** from the top bar (Add, Push, Throw, Freeze, or Reset)
4. **Interact** with objects on the canvas:
   - *Add Mode*: Click to place objects
   - *Push Mode*: Click and drag to apply force
   - *Throw Mode*: Click and drag to set velocity
5. **Adjust parameters** using the sidebar sliders:
   - Environment: gravity, friction, bounciness
   - Object: mass
6. **Toggle forces** on/off to focus on specific physics concepts
7. **View formulas** to see live calculations

## Physics Concepts

This simulator visualizes:
- **Newton's Second Law**: $F = ma$
- **Friction**: $F_f = \mu N$
- **Weight**: $F_g = mg$
- **Net Force**: $\Sigma F = F_{\text{net}}$
- **Elastic Collisions**: Based on restitution coefficient
- **Projectile Motion**: Gravity-driven motion with applied forces

## Technical Stack

- **Pure HTML5 Canvas** for rendering
- **Vanilla JavaScript** for physics engine and interactions
- **CSS** for styling (dark theme UI)

## Browser Compatibility

Works on all modern browsers supporting HTML5 Canvas and ES6 JavaScript.
