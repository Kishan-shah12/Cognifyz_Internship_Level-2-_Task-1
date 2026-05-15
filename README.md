# 🚀 Cognifyz Internship - Level 2 | Task 1

## Responsive Web Components with CSS Frameworks

<div align="center">
  <p><i>A demonstration of using modern CSS frameworks (Bulma & Bootstrap) to build premium, responsive, and interactive web components.</i></p>
</div>

---

## 🌟 Project Overview

The objective of this task was to demonstrate proficiency in using popular CSS front-end frameworks to build responsive designs quickly and efficiently. The project consists of two separate HTML files, each utilizing a different framework to prevent CSS clashing, while also incorporating custom premium aesthetics.

### 🎯 Key Objectives Met:
1. **Framework Integration:** Successfully imported and utilized **Bulma** and **Bootstrap 5** via CDNs.
2. **Responsive Design:** Both components natively adapt to mobile, tablet, and desktop screens using framework-specific grid and column classes.
3. **Interactive Modals:** Built native "Read More" and "Explore" popup modals to display additional content dynamically without creating new pages.
4. **Premium Aesthetics:** Enhanced default framework styles with custom CSS for glassmorphism, animated gradients, and staggered entrance animations.

---

## 🎨 Visual Preview & Structure

### 1. Responsive Card Component (`card.html`)
**Framework Used:** Bulma CSS

This component features a modern "Glassmorphism" card sitting on top of a continuously animated color gradient. It includes hover zoom effects, a pulsing action button, and a fully functional Bulma Modal that opens to reveal a course curriculum.

<div align="center">

![Glassmorphism Card Preview](/Users/kishansah/.gemini/antigravity/brain/8a3dc77b-66c4-49e6-b274-b1087d0e715f/task1_card_preview_1778581492184.png)

</div>

### 2. Responsive Grid Layout (`grid.html`)
**Framework Used:** Bootstrap 5

A sleek, dark-themed "Services" section demonstrating Bootstrap's powerful responsive grid system (`col-12 col-md-6 col-lg-4`). It features staggered fade-in animations on load, glowing hover states, gradient text, and individual Bootstrap Modals for each card.

<div align="center">

![Dark Mode Grid Preview](/Users/kishansah/.gemini/antigravity/brain/8a3dc77b-66c4-49e6-b274-b1087d0e715f/task1_grid_preview_1778581512218.png)

</div>

---

## 🛠️ Technical Implementation Details

### CSS Frameworks vs Custom CSS
While the core layout, spacing, and modal functionality strictly rely on **Bulma** and **Bootstrap** utility classes, custom `<style>` blocks were strategically injected to elevate the visual hierarchy.

#### Highlight: The Glassmorphism Effect (Bulma)
```css
.glass-card {
    background: rgba(255, 255, 255, 0.85);
    backdrop-filter: blur(12px);
    border: 1px solid rgba(255, 255, 255, 0.4);
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
}
```

#### Highlight: Gradient Typography (Bootstrap)
```css
.gradient-text {
    background: linear-gradient(135deg, #38bdf8 0%, #818cf8 100%);
    -webkit-background-clip: text;
    background-clip: text; /* Standard property for compatibility */
    -webkit-text-fill-color: transparent;
}
```

### Interactive Modals
* **Bulma Modals:** Handled via custom Vanilla JavaScript to toggle the `is-active` class on the modal container when the "Read More" button or background overlay is clicked.
* **Bootstrap Modals:** Handled natively via Bootstrap's bundled JavaScript using data attributes (`data-bs-toggle="modal"` and `data-bs-target="#modalId"`).

---

## 💻 How to Run

1. Clone or download the repository to your local machine.
2. Navigate to the `Cognifyz_Internship_Level 2 _Task 1` directory.
3. Open `card.html` or `grid.html` directly in any modern web browser.
4. **Testing Responsiveness:** Resize your browser window to see how the Bulma columns and Bootstrap grid adapt.
5. **Testing Interactivity:** Click the "Read More" or "Explore" buttons to trigger the detailed pop-up modals.

---

<div align="center">
  <p><b>Built by Kishan Sah</b></p>
</div>
