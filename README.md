# Stacked Card Layout

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-success)
![Status](https://img.shields.io/badge/Project-Active-blue)

A modern, responsive stacked-card UI built with pure HTML and CSS. Cards animate from a stacked layout into a horizontal spread with smooth hover transitions. Fully responsive and mobile-friendly.

---
## Demo Preview

<div style="text-align: center;">
  <img src="assets/demo.gif" alt="Demo Preview">
</div>

## Live Demo
You can check out the stacked card layout in action [here](https://oussamale.github.io/stacked-card-layout/).

---
## Features

- **Modern UI**: Gradients, shadows, clean typography

- **Interactive Cards**: Stacked layout, horizontal spread on hover, staggered content reveal

- **Responsive**: Works on tablet and mobile, hover disabled on touch devices

- **Pure CSS**: No JavaScript, smooth hardware-accelerated transitions

---



## Project Structure

```
stacked-card-layout/        # Root folder for the project
│
├── README.md               # Project documentation
├── index.html              # Main HTML file
├── style.css               # CSS file for styling and animations
└── assets/                 # Folder for media assets
    └── demo.gif            # Demo GIF showing the stacked-card UI in action
```


---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/oussamale/stacked-card-layout.git
cd stacked-card-layout
```

### Open in Your Browser
On Mac
```bash
open index.html
```

On Windows
```bash
start index.html
```

On Linux
```bash
xdg-open index.html
```

## Customization


### Add or Remove Cards

Duplicate a card block:

```html
<div class="card" style="--i:VALUE;">
    <div class="card-content" style="--j:VALUE;">
        <h2 class="card-title">Title</h2>
        <p class="card-text">Text...</p>
    </div>
</div>
```


### Customize Card Stack
Each card uses CSS variables for stacking and animation:
- `--i` → card stacking offset
- `--j` → animation delay

### Change Colors

Modify gradients in style.css:
```CSS
background: linear-gradient(135deg, #1a2a6c, #2a3a8c, #4a4a8c);
```
### Adjust Animation Timing

Modify transition speeds:
```CSS
transition: all 0.5s cubic-bezier(...);
```


## Credits
Created by Oussama.
Contributions, suggestions, feedback and forks are welcome!

