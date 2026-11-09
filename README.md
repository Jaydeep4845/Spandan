# Spandan

A hospital website where patients can create an account, book an appointment with a department,
and read health information.

> Learning project from 2023, built to practise front-end development and Firebase authentication.

## Features

- Sign up and log in with Firebase Authentication (email and password)
- Appointment booking form: name, contact, case type (new, follow-up, emergency) and department
  (general, brain, lung, heart, surgery)
- Pages for facilities, consultation pricing, healthy-living tips and hospital information

## Structure

```
home_page/     landing page, login, sign-up and Firebase auth logic
appointment/   booking form and appointment pages
extra/         health tips and information pages
```

## Run it

No build step. Open `home_page/home.html` in a browser. Authentication needs a Firebase project
with email/password sign-in enabled; put its web config in `home_page/auth.js`.

## Tech stack

HTML, CSS, Bootstrap, JavaScript, Firebase Authentication.
