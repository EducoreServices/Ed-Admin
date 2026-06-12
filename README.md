# HR Onboarding Application Form

This repository contains the source code for a responsive, admissions-style HR onboarding application form built in HTML and CSS. The form is designed to match the style and layout of the Educore admissions online application first page, with a grey-themed color palette for a professional and clean user interface.

## Features

- Multi-section form with five main steps:
  - Personal Details
  - Employment
  - Contact
  - Area & Access
  - Declaration
- Responsive two-column layout consistent with Educore admissions style
- Clear indication of mandatory fields with green badges and red asterisks
- Accessible form elements with proper labels and tab order
- Placeholder support for date fields with instructions for datepicker integration
- Validation for required fields with review and submission alerts
- Separate HR payroll review workflow (payroll fields removed from this form)
- Grey color theme for a neutral, professional look

## Usage

- Open the `index.html` file in any modern web browser to view and interact with the form.
- Integrate with backend services to handle form submission, draft saving, and HR review workflows.
- Add a JavaScript datepicker library to enhance date input fields (`BirthDate`, `StartDate`, `SignatureDate`).
- Customize logos and branding by replacing the placeholders in the header section.

## File Structure

- `index.html` — The main HTML file containing the form markup, styles, and basic front-end validation scripts.

## Customization

- Modify CSS variables in the `<style>` section to adjust colors, fonts, and spacing.
- Extend the form with additional fields or steps as needed.
- Implement backend APIs to process form data, save drafts, and manage HR review.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## MIT License

