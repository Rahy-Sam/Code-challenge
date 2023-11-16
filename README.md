# Code-challenge
# REACT APPLICATION THAT FETCHES DATA FROM A JSON SERVER AND DISPLAYS IT USING VARIOUS COMPONENTS.
# USAGE:
* Ensure that you have React installed in your project.

* bash
* Copy code
* npm install react
* Component Integration:
* Import the Form component into your desired file.

jsx
Copy code
import React from 'react';
import Form from './path/to/Form';
Rendering the Form:
Include the <Form /> component within your parent component's render method.

jsx
Copy code
function YourComponent() {
  return (
    <div>
      {/* Other components */}
      <Form />
      {/* Other components */}
    </div>
  );
}
Form Fields:
The form includes the following fields:

Date: Allows users to select a date.
Description: Captures a brief description of the transaction.
Category: Specifies the category of the transaction.
Amount: Records the transaction amount.
Ensure that all fields marked with an asterisk (*) are filled in before submitting the form.

Adding a Transaction:
Click the "Add transaction" button to submit the form and add a new transaction.
This form component assumes the existence of a parent component managing state and handling the submission of the form data.
Feel free to customize the form component and integrate it seamlessly into your React application!

Components
Header
The header component provides the title of the application.

SearchBar
A simple search bar to filter transactions.

Form
The form component allows users to input transaction details, including date, description, category, and amount. Click the "Add transaction" button to submit a new transaction.

TableTransaction
This component displays the transaction data in a table format.

Fetching Data
The application fetches transaction data from a JSON server:
Contributing
Feel free to contribute to the development of this project. Fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License.

Author: Raymond Mwaiki
