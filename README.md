# survey-form-freeCodeCamp
01 Project For Responsive Web Design

## Build a Survey Form
Objective: [Build an app that is functionally similar to ](https://survey-form.freecodecamp.rocks)

## User Stories:
1. You should have a page title in an h1 element with an id of title
1. You should have a short explanation in a p element with an id of description
1. You should have a form element with an id of survey-form
1. Inside the form element, you are required to enter your name in an input field that has an id of name and a type of text
1. Inside the form element, you are required to enter your email in an input field that has an id of email
1. If you enter an email that is not formatted correctly, you will see an HTML5 validation error
1. Inside the form, you can enter a number in an input field that has an id of number
1. The number input should not accept non-numbers, either by preventing you from typing them or by showing an HTML5 validation error (depending on your browser).
1. If you enter numbers outside the range of the number input, which are defined by the min and max attributes, you will see an HTML5 validation error
1. For the name, email, and number input fields, you can see corresponding label elements in the form, that describe the purpose of each field with the following ids: id="name-label", id="email-label", and id="number-label"
1. For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field
1. Inside the form element, you should have a select dropdown element with an id of dropdown and at least two options to choose from
1. Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the name attribute
1. Inside the form element, you can select several fields from a series of checkboxes, each of which must have a value attribute
1. Inside the form element, you are presented with a textarea for additional comments
1. Inside the form element, you are presented with a button with id of submit to submit all the inputs
1. Fulfill the user stories and pass all the tests below to complete this project. Give it your own personal style. Happy Coding!

Note: Be sure to add `<link rel="stylesheet" href="styles.css">` in your HTML to link your stylesheet and apply your CSS

----

## Tests

1. Waiting: You should have an h1 element with an id of title.
1. Waiting: Your #title should not be empty.
1. Waiting: You should have a p element with an id of description.
1. Waiting: Your #description should not be empty.
1. Waiting: You should have a form element with an id of survey-form.
1. Waiting: You should have an input element with an id of name.
1. Waiting: Your #name should have a type of text.
1. Waiting: Your #name should require input.
1. Waiting: Your #name should be a descendant of #survey-form.
1. Waiting: You should have an input element with an id of email.
1. Waiting: Your #email should have a type of email.
1. Waiting: Your #email should require input.
1. Waiting: Your #email should be a descendant of #survey-form.
1. Waiting: You should have an input element with an id of number.
1. Waiting: Your #number should be a descendant of #survey-form.
1. Waiting: Your #number should have a type of number.
1. Waiting: Your #number should have a min attribute with a numeric value.
1. Waiting: Your #number should have a max attribute with a numeric value.
1. Waiting: You should have a label element with an id of name-label.
1. Waiting: You should have a label element with an id of email-label.
1. Waiting: You should have a label element with an id of number-label.
1. Waiting: Your #name-label should contain text that describes the input.
1. Waiting: Your #email-label should contain text that describes the input.
1. Waiting: Your #number-label should contain text that describes the input.
1. Waiting: Your #name-label should be a descendant of #survey-form.
1. Waiting: Your #email-label should be a descendant of #survey-form.
1. Waiting: Your #number-label should be a descendant of #survey-form.
1. Waiting: Your #name should have a placeholder attribute and value.
1. Waiting: Your #email should have a placeholder attribute and value.
1. Waiting: Your #number should have a placeholder attribute and value.
1. Waiting: You should have a select field with an id of dropdown.
1. Waiting: Your #dropdown should have at least two selectable (not disabled) option elements.
1. Waiting: Your #dropdown should be a descendant of #survey-form.
1. Waiting: You should have at least two input elements with a type of radio (radio buttons).
1. Waiting: You should have at least two radio buttons that are descendants of #survey-form.
1. Waiting: All your radio buttons should have a value attribute and value.
1. Waiting: All your radio buttons should have a name attribute and value.
1. Waiting: Every radio button group should have at least 2 radio buttons.
1. Waiting: You should have at least two input elements with a type of checkbox (checkboxes) that are descendants of #survey-form.
1. Waiting: All your checkboxes inside #survey-form should have a value attribute and value.
1. Waiting: You should have at least one textarea element that is a descendant of #survey-form.
1. Waiting: You should have an input or button element with an id of submit.
1. Waiting: Your #submit should have a type of submit.
1. Waiting: Your #submit should be a descendant of #survey-form.
1. 