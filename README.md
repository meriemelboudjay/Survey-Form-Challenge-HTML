<div align="center">

# freeCodeCamp Survey Form

A responsive, accessible survey form built with plain HTML and CSS.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/status-complete-34ad63)

[Live Demo](https://survey-form-challenge-html.vercel.app/) · [Report a Bug](https://github.com/meriemelboudjay/Survey-Form-Challenge-HTML/issues)

<img src="images/the%20Result.png" alt="Survey form preview" width="600">

</div>

---

## About

This project is a user feedback survey inspired by freeCodeCamp. It was built as part of the **Responsive Web Design** certification and focuses on writing clean semantic HTML, using native form controls and validation, and styling a polished interface without any framework or JavaScript.

## Features

- **Native validation:** the name and email fields are required, and the browser checks the email format.
- **Varied input types:** text, email, number, select, radio, checkbox, and textarea.
- **Sensible defaults:** disabled placeholder options in dropdowns and a pre-selected radio answer.
- **Readable design:** a dark form card over a purple image overlay, with high-contrast text.
- **Responsive layout:** the form fits any screen, from phones to wide desktops.
- **No dependencies:** no build step, framework, or external library.

## Survey Content

| Question | Control | Required |
|----------|---------|:--------:|
| Name | Text input | ✅ |
| Email | Email input | ✅ |
| Age | Number input | |
| Current role | Dropdown | |
| Would you recommend freeCodeCamp to a friend? | Radio group | |
| Favorite feature of freeCodeCamp | Dropdown | |
| What would you like to see improved? | Checkbox group (11 options) | |
| Comments or suggestions | Textarea | |

## Tech Stack

- **HTML5:** semantic structure (`header`, `main`, `form`) and built-in form validation
- **CSS3:** attribute selectors, `linear-gradient` overlay, responsive widths with `max-width`

## Getting Started

No installation is needed.

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo.git

# Move into the project folder
cd your-repo
```

Then open `index.html` in your browser, or serve the folder with a tool such as the VS Code **Live Server** extension.

## Project Structure

```
survey-form/
├── images/
│   ├── teamWork.jpg # Page background
|   ├── the Exercice.png  # Screenshot used in exercice
│   └── the Result.png     # Screenshot used in this README
├── index.html          # Markup
├── style.css           # Styles
└── README.md
```

## Design Decisions

- **Background overlay:** a semi-transparent gradient sits on top of the photo so white text remains readable whatever the image looks like.
- **Fluid card width:** the form uses `width: 90%` with `max-width: 500px`, so it never stretches too wide or overflows on small screens.
- **Consistent controls:** inputs, selects, and the textarea share a full-width layout, and `box-sizing: border-box` keeps their sizes predictable.

## Roadmap

- [ ] Gray placeholder text on dropdowns using `required` and `:invalid`
- [ ] Group radios and checkboxes with `<fieldset>` and `<legend>`
- [ ] Visible focus styles for keyboard navigation
- [ ] Confirmation message after submission
- [ ] Connect the form to a backend or form service to store responses

## Author
GitHub: [@meriemelboudjay](https://github.com/meriemelboudjay)

## License

Released under the [MIT License](LICENSE). Free to use for learning and reference.
