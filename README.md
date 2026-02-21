# richi-shcool

A simple web-based password validator built with HTML and JavaScript.

## Description

This project provides a client-side password validation form that checks whether a password meets the following requirements:

- **Not empty** – The field must not be left blank.
- **Minimum length** – At least 8 characters.
- **Uppercase letter** – Must contain at least one uppercase letter (A–Z).
- **Number** – Must contain at least one digit (0–9).

## Files

| File | Description |
|------|-------------|
| `Richi/Richi.html` | Main HTML page with the password validation form and inline JavaScript logic. |

## Usage

1. Open `Richi/Richi.html` in any modern web browser.
2. Type a password in the input field.
3. Click the **Validar** button.
4. A message will appear indicating whether the password is valid or describing which requirement is not met.

## Validation Rules

| Rule | Error Message |
|------|---------------|
| Empty field | `Obligatoria` |
| Fewer than 8 characters | `Mínimo 8 caracteres` |
| No uppercase letter | `Falta mayúscula` |
| No digit | `Falta número` |
| All rules met | `Contraseña válida ✅` |

## Technologies

- HTML5
- Vanilla JavaScript (no external libraries required)
