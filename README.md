<div align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/Pranav-Jadhav09/signup-forms)
[![Twitter Follow](https://img.shields.io/twitter/follow/Pranav_Jadhav09?style=social)](https://twitter.com/Pranav_Jadhav09)

<br />
<br />

<h2 align="center">Sign Up Form</h2>
This Repo Contains the Forms projects made while learning JavaScript. Has Validations, Completely Responsive.

<a href="https://sign-up-form-n7iv.onrender.com/"><strong>➥ Live Demo</strong></a>

</div>

<br />

## Validations 

### Email Validation
- Pattern: ^[^ ]+@[^ ]+\.[a-z]{2,3}$

- Description: Validates that the input adheres to a standard email format.

### Password Validation

- Pattern: ^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,}$

- Description: Ensures that the password:
- Contains at least one lowercase letter
- Contains at least one uppercase letter
- Contains at least one digit
- Contains at least one special character from [@, $, !, %, *, ?, or &]
- Is at least 8 characters long

### Hide and Show Password
- The application provides an option to hide/show the password input text.

### Confirm Password Validation
- This project does not currently implement confirm password validation, but you can extend the existing pattern for this purpose.
- These validations are integrated into the project by associating the validation functions with relevant form events such as form submission and keyup events for real-time feedback to the user.


## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Git](https://git-scm.com/downloads "Download Git") must be installed on your operating system.

## Run Locally

To run **FORMS**, run this command on your git bash:

Linux and macOS:

```bash
sudo git clone https://github.com/Pranav-Jadhav09/signup-form.git
```

Windows:

```bash
git clone https://github.com/Pranav-Jadhav09/signup-form.git
```

## License

MIT
