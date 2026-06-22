# Sign-Up Form

A responsive sign-up form built as part of [The Odin Project](https://www.theodinproject.com/) curriculum.

## Preview

The layout features a two-panel design:
- **Left panel** — full-height background photo with a logo banner and photo credit
- **Right panel** — sign-up form with input validation

## Features

- Two-column form layout using Flexbox
- Fields: First Name, Last Name, Email, Phone Number, Password, Confirm Password
- HTML5 input validation (`required`, `type="email"`, `type="tel"`, `type="password"`)
- Focus styles with a blue highlight on active inputs
- Custom `Norse` font for the logo banner
- Responsive card-style form with subtle box shadow
- Form submits to [httpbin.org/post](https://httpbin.org/post) for testing (no real data is stored)

## Project Structure

```
.
├── index.html
├── style.css
├── fonts/
│   └── Norsebold.otf
└── images/
    ├── logo.png
    └── background.jpg
```

## Usage

Just open `index.html` in any modern browser — no build step or dependencies needed.

> ⚠️ This is a practice project. Do not enter any real personal information.

## Credits

- Background photo by [Simon Migaj](https://unsplash.com/@simonmigaj) on [Unsplash](https://unsplash.com/)
- Built as part of [The Odin Project](https://www.theodinproject.com/) — Full Stack JavaScript path
