# Just a Card
# Profile Card

A simple profile card layout built with semantic HTML and modern CSS. The card presents a person's photo alongside their role and location, making it perfect for a quick LinkedIn-like introduction or portfolio snippet.

## Preview

![Profile Card Preview](./images/per.png)

> Tip: The preview uses the bundled sample image. Replace it with your own photo to personalize the card.

## Features

- Responsive flexbox layout that keeps the image and text aligned.
- Clean typography with centered stacking for name, role, and location.
- Object-fit handling to ensure the profile image neatly fills its frame.
- Subtle drop shadow and background color to help the card pop against the page.

## File Structure

`
.
+-- index.html   # Markup for the card component
+-- style.css    # Styling for layout, typography, and card aesthetics
+-- images/
    +-- per.png  # Sample profile photo used in the demo
`

## Getting Started

1. Clone the repository or download the project files.
2. Open index.html directly in your browser to see the card.
3. Customize the content in index.html by editing the name, job title, and location.
4. Update the image source to your own photo (place it inside images/ and adjust the path if needed).

## Customization

- **Spacing:** Adjust the gap, padding, or margin values inside style.css to fine-tune layout spacing.
- **Colors:** Change the ackground-color of .cmain or the ox-shadow color to match your brand.
- **Typography:** Update font sizes by editing the .c1 h3, .c1 p, and .c1 h4 rules in style.css.
- **Fonts:** Add a Google Font by linking it in index.html and applying it via CSS.

## License

This project is open for personal and educational use. Feel free to remix and share with attribution.