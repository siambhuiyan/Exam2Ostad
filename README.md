# Form Submission Page


This application provides a form for users to submit their personal details including **Name**, **Age**, and **Salary**. The form ensures that all fields are filled in correctly and follows specific input rules for **Age** and **Salary**.

## Features

### 1. **Name Input**
- The user is required to enter their name.
- The input cannot be left empty. A prompt will notify the user to fill in this field if left blank.

![Name Input Image](./assets/img1.jpg)

### 2. **Age Input**
- The user is required to input their **Age** in numbers.
- Only numeric keyboard input is allowed to ensure valid data entry.
- The field cannot be left empty.
- If the user tries to submit the form with a non-numeric value, a validation error message will appear.

![Age Input Image](./assets/img4.jpg)

### 3. **Salary Input**
- The user is required to input their **Salary** in numbers.
- Only numeric keyboard input is allowed.
- The field cannot be left empty.
- If a non-numeric value is entered, a validation error will notify the user.

![Salary Input Image](./assets/img3.jpg)

## Validation Rules
- All fields (**Name**, **Age**, and **Salary**) must be filled out correctly before submission.
- **Name** should be a string containing alphabets (and possibly spaces).
- **Age** and **Salary** should only contain numerical values.
- If the user tries to submit empty fields or enters invalid data, a respective validation error message will be displayed.

![Salary Input Image](./assets/img2.jpg)

## Instructions for Users

1. Fill out the form with your **Name**, **Age**, and **Salary**.
2. Ensure that:
    - The **Name** field is not left empty.
    - The **Age** and **Salary** fields only contain numbers.
3. If you encounter any validation errors, make sure to correct the input and submit the form again.
