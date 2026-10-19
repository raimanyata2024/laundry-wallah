# Laundry Wallah / Laundry Mart

A simple laundry service website built using HTML. This beginner-friendly project introduces the basic structure of a website and includes a list of laundry services, a price list, and a booking form.

## Features

- Welcome section introducing Laundry Wallah / Laundry Mart
- Washing machine image
- List of available laundry services
- Price list for selected services
- Booking form with name, email, and phone number fields
- Basic browser-side form validation using HTML attributes
- Service selection and pickup date fields can be added to extend the form

## Technologies Used

- HTML5

## Project Structure

Keep the HTML file and image in the same folder:

```text
laundry-wallah/
├── index.html
├── task2.png
└── README.md
```

If the image is stored in a different folder, update the `src` path in the `<img>` element.

## How to Run

1. Download or clone this project.
2. Make sure `index.html` and `task2.png` are in the correct locations.
3. Open `index.html` in a web browser.

You can also open the project folder in Visual Studio Code and use a local preview extension.

## Form Validation

The booking form can use HTML attributes such as:

- `required` to require a field
- `type="email"` to check the general format of an email address
- `type="tel"` for phone-number input
- `pattern="[0-9]{10}"` to require exactly 10 digits
- `maxlength="10"` to limit the phone number to 10 characters

These checks improve usability, but they do not verify that an email address or phone number is genuine.

## Current Limitations

- The project uses HTML only; it does not include a backend or database.
- Booking submissions are not saved or sent to the laundry service.
- HTML validation is not a security boundary and can be bypassed.
- The page has basic structure and can be enhanced with CSS for styling and JavaScript for client-side interactions.

## Future Improvements

- Add CSS for a responsive layout and improved visual design.
- Add service selection and a pickup date to the booking form.
- Use JavaScript for additional client-side interactions.
- Connect a backend and database to securely receive and store bookings.
- Add server-side validation before accepting submitted data.

## Purpose

This project is intended for learning and practicing basic HTML elements, including headings, paragraphs, images, lists, tables, labels, inputs, and buttons.
