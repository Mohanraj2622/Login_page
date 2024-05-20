# Login Page Template

This is a simple HTML login page template styled with CSS. It includes fields for ID, name, and password, and buttons for login, signing up, and password recovery.

## Features

- Responsive design with a centered login form.
- Customizable background image.
- Styled input fields and submit button.
- Links for signing up and password recovery.

## Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/login-page-template.git
    cd login-page-template
    ```

2. **Open the HTML file**:
    Open the `index.html` file in your web browser to view the login page.

## Files

- `index.html`: The main HTML file containing the login form.
- `wallhaven-jxvvx5.jpg`: Background image used in the login page.

## HTML Structure

- `<!DOCTYPE html>`: Declares the document type.
- `<html>`: Root element of the HTML document.
- `<head>`: Contains metadata and the CSS styling for the page.
- `<style>`: Defines the CSS styles used in the document.
- `<body>`: Contains the content of the page, including the login form.

## CSS Styles

- **Background Image**:
  ```css
  body {
      background-image: url('wallhaven-jxvvx5.jpg');
      background-size: 2000px;
      font-family: Arial, sans-serif;
  }
  ```
  Sets a background image and font for the page.

- **Container**:
  ```css
  .container {
      width: 300px;
      background-color: #fff;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
      margin: 50px auto;
  }
  ```
  Styles the container holding the login form with a white background, padding, rounded corners, and a box shadow.

- **Form Elements**:
  ```css
  h2 {
      text-align: center;
      margin-bottom: 20px;
  }
  label {
      display: block;
      margin-bottom: 5px;
  }
  input[type="text"],
  input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
  }
  input[type="submit"] {
      background-color: #4CAF50;
      color: white;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      width: 100%;
  }
  input[type="submit"]:hover {
      background-color: #45a049;
  }
  ```
  Styles the form elements, including input fields and the submit button.

## Form Structure

- `<h2>Login</h2>`: Heading for the login form.
- `<form>`: Form element with fields for ID, name, and password, and a submit button.
- `<label>`: Labels for each input field.
- `<input>`: Input fields for ID, name, and password, and a submit button.

## Links

- **Sign up**:
  ```html
  <p>Don't have an account? <a href="#">Sign up</a></p>
  ```
  Link for users to sign up for an account.

- **Forget Password**:
  ```html
  <p><a href="#">Forget Password?</a></p>
  ```
  Link for users to recover their password.

## Customization

- **Background Image**: Change the `background-image` URL in the CSS to use a different image.
- **Container Width**: Adjust the `width` property of the `.container` class to change the form's width.
- **Colors**: Modify the `background-color` and `color` properties in the CSS to change the form's colors.


## Acknowledgments

- Inspired by various login page designs and CSS styling techniques.


