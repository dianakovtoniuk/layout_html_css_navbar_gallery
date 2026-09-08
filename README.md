Responsive Navbar and Photo Gallery

Running: https://dianakovtoniuk.github.io/layout_html_css_navbar_gallery/

A mobile-first layout exercise built with plain HTML and CSS. Includes a responsive navigation bar and a responsive photo gallery with a featured (larger) image.

Features

Navigation bar
Mobile: items stacked vertically, centered
Tablet and up (768px+): items in a single row, aligned to the end

Photo gallery
Mobile: single column
Tablet (768px+): two columns
Laptop and up (1024px+): three columns, with the third image enlarged to span 2 columns and 2 rows

Tech

HTML5
CSS Grid, Flexbox
Media queries (mobile-first approach)

Project structure

index.html
style.css

Breakpoints

Mobile: default
Tablet: 768px+
Laptop: 1024px+

Notes

Grid item order was set explicitly for the featured layout instead of relying on grid-auto-flow: dense, to keep image order matching the source markup.
Images use object-fit: cover to fill their grid cell without distortion.
