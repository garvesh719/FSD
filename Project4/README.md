# Interactive 3D Flip Card using HTML & CSS

## 🎯 Objective
Create a 3D flip card that rotates 180° on hover to reveal content on the back, using only HTML and CSS.

## 🛠 Requirements

### 1. Card Structure (HTML)
- Use semantic HTML (`<article>`, `<div>`, `<h3>`, `<p>`, `<img>`).
- Each card must include:
  - Front face: image, title, short tagline.
  - Back face: description, skills, or call-to-action button.
- Wrap in a container for the flip effect.

### 2. 3D Flip Effect (CSS)
- On hover: card flips horizontally around Y-axis (`transform: rotateY(180deg)`).
- Smooth transition (0.6s, ease).
- Use:
  - `transform-style: preserve-3d`
  - `perspective` for depth
  - `backface-visibility: hidden`

### 3. Visual Design
- Distinct styles for front/back.
- Clean, modern font (Google Fonts: Poppins, Montserrat).
- Subtle shadows (`box-shadow`) and rounded corners.

### 4. Image & Content
- Placeholder or real image on front.
- Back: short description + styled button ("Learn More").

## 📦 Deliverables
- `index.html` — semantic HTML structure.
- `style.css` — clean, commented CSS using transforms.
