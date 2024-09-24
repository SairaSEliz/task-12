# Task-12: Registration Page with CSS and JavaScript Validation

## Project Description

This project involves creating a simple registration page with fields for:
- First Name
- Last Name
- Email ID
- Phone Number
- Password
- Confirm Password

The form submission leads to a confirmation page that informs the user they have been registered.

## Files in the Project

- **index.html**: Main registration page with the form.
- **submit.html**: Confirmation page shown after form submission.
- **style.css**: CSS file to style the registration form and page.
- **script.js**: JavaScript file to handle password matching validation.

## Steps to Run the Project

1. **Open in VSCodium**:
   - Clone the repository to your local machine or create the files manually in VSCodium.
    I. Add the VSCodium GPG Key and Repository:
```
wget -qO - https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo/raw/master/pub.gpg \
    | gpg --dearmor \
    | sudo dd of=/usr/share/keyrings/vscodium-archive-keyring.gpg
```
   II. Add the repository:
   ```
    echo 'deb [ signed-by=/usr/share/keyrings/vscodium-archive-keyring.gpg ] https://download.vscodium.com/debs vscodium main' \
    | sudo tee /etc/apt/sources.list.d/vscodium.list
```
  III. Update the Package List:
  ```
     sudo apt update
```
  IV. Install VSCodium:
  ```
     sudo apt install codium
```
 V. Open VScodium in kali terminal 
 ```
codium
```

2. **Run with Live Server**:
   - Ensure Live Server is installed in VSCodium.
   - Right-click on `index.html` and select **Open with Live Server**.
   - Your web browser should open with the registration form.

3. **Form Functionality**:
   - Fill in the form and submit it.
   - Ensure the **Password** and **Confirm Password** fields match. If not, an alert will appear.
   - On successful submission, the form will redirect to `submit.html`.

## CSS Styling

The form is styled with basic CSS rules:
- The form is aligned at the center of the page.
- Fields have a clean, modern design with padding and borders.
- The submit button has a green color scheme with a hover effect.

## JavaScript Validation

Password matching is checked using JavaScript:
- If the passwords do not match, the form submission is prevented, and an alert is displayed.
- The JavaScript for this functionality has been moved into a separate file (`script.js`).

## How to Use the Project

- Download or clone this repository.
- Open the project in VSCodium.
- Use Live Server to preview the `index.html` file and test the form submission.

## Repository Structure

