# Form Controls

## Project Overview
A simple T-shirt order form developed as part of a web development exercise to practise creating semantic, accessible HTML forms and using native HTML form validation.

The form is designed for existing customers, so it collects only the information required to confirm their identity and specify their T-shirt preferences: name, email address, colour, and size. All fields are required.

The name field uses a regular expression with the HTML `pattern` attribute to ensure that it contains at least two non-space characters, while the email field uses the `email` input type for built-in format validation. The T-shirt colour is selected using radio buttons, providing exactly three choices — red, blue, and green — and the size is selected from a list containing XS, S, M, L, XL, and XXL.

The project was implemented using HTML and CSS only, without JavaScript.

## Live Demo
[View the live T-shirt order form](https://fromonda.github.io/Form-Controls/)
