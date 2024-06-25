# Progress Log

## 2024-06-24 - Morning

### Project Setup

- Set up the project files.

### Design Review

- Reviewed the [Figma file](https://www.figma.com/design/hL7QWg3uxJ9CIUI6F5ku4l/art-gallery-website?node-id=40-329&t=53zjCtXtwaIKGBXr-0) to:
  - Identified the sections, main elements/components, and the [macro layout](../design/01-composition.jpg).
  - Further identified the components and determined the [micro layout](../design/02-components.jpg) for those elements.

## 2024-06-24 - Afternoon

### Hero Section

- Developed a responsive hero section by leveraging the [`l-canvas` class](https://github.com/nicholasgillespie/art-gallery/blob/main/src/styles/40-layouts/_canvas.scss) for layout and implementing CSS grid and responsive design tweaks for adherence to the design file.
- Used `<picture>` and `<source>` for optimized images across devices.

### Project Setup

- Initialized the project on [GitHub](https://github.com/nicholasgillespie/art-gallery).
- Deployed the project to [GitHub Pages](https://nicholasgillespie.github.io/art-gallery/).

#### TODO

- Define project design tokens.
- Correct accessibility issue, redundant h1 element.
- Change file png format to jpg for display layout images.

## 2024-06-25 - Afternoon

### Accessibility and File Format Adjustments

- Corrected the accessibility issue with redundant `h1` elements.
- Changed image files from PNG format to JPG to improve load times and consistency.

### Design Tokens

- Defined most of the project [design tokens](https://github.com/nicholasgillespie/body-mass/tree/main/src/styles/00-settings). Remaining tasks include updating the font-size design token.

### Head Section Development

- Continued work on the head section, implementing an accessible button with an arrow that supports contrast theme adjustments.

#### TODO

- Update the font-size design token to ensure consistency across all components.
- Ensure all reusable components / files use the scss get function (button, skiplink, etc.).
- Implement Gallery section. Use [grid-template-areas](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas).

---

## [Date] - [Session]

### [Task Category]

- [Your tasks here]
