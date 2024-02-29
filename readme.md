# HTML Resume

## Live Demo

The project "My resume" can be found at: [https://dupontdenis.github.io/myResume/](https://dupontdenis.github.io/myResume/)

## Description

This project is a responsive HTML resume that uses CSS Flexbox for layout. It's designed to provide a concise overview of my skills, experience, and education.

## Features

- Responsive design that looks good on all devices
- Uses CSS Flexbox for efficient and flexible layout
- Easy to customize with your own details
- Developed with the assistance of GitHub Copilot

## Copilot

The animation for the stars in the skills section was generated with the assistance of GitHub Copilot. The stars change color from gray to yellow from left to right when hovered over, creating a smooth and visually appealing effect. Here's the CSS code used for the animation:

```css
.stars {
  background: linear-gradient(to right, #ccc 50%, gold 50%);
  background-size: 200% 100%;
  background-position: 100% 0;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  transition: background-position 0.5s;
}

.stars:hover {
  background-position: 0 0;
}
```

## How to View

To view the resume, simply open the `index.html` file in your web browser.

## Customization

To customize the resume with your own details, edit the `index.html` file. Replace the placeholder text with your own information.

## License

This project is open source and available under the [MIT License](LICENSE).
