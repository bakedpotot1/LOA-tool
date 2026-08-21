# Letter of Authorisation Creator

A web-based tool built with HTML, CSS and JavaScript to streamline the creation of Letters of Authorisation (LOAs).

This project was originally created to solve a repetitive operational process that required advisors to manually create and format letters for different countries and carriers.

## The Problem

Creating Letters of Authorisation was a repetitive and time-consuming task.

Advisors needed to:

- Manually enter order and shipment information
- Use different templates depending on the country
- Include different information depending on the required process
- Format the letters correctly
- Download the completed letter for use

The process could take several hours to complete and was prone to human error.

## The Solution

I taught myself HTML, CSS and JavaScript and built a simple web application to automate much of the process.

The user can:

1. Select the required action
2. Select the relevant country
3. Enter the required shipment and order information
4. Generate the appropriate Letter of Authorisation

The application uses JavaScript logic to determine which template should be used and which information is required for different countries.

## Features

- Country-specific letter templates
- Dynamic form fields based on the selected country and action
- Automatic routing to the appropriate LOA template
- Form validation and data collection
- Local storage used to transfer information between pages
- Automatic population of letter templates
- Printable completed letters

## Technologies Used

- HTML
- CSS
- JavaScript

## Project Structure

- `index.html` – Main application and user input form
- Country-specific HTML files – Templates for different Letter of Authorisation requirements
- JavaScript – Handles user input, conditional logic, routing and data population
- CSS – Styling and responsive layout

## What I Learned

This was one of my first larger self-taught development projects and gave me practical experience with:

- HTML, CSS and JavaScript
- Conditional logic
- Event listeners
- Form handling
- Working with multiple files
- Using `localStorage`
- Dynamically showing and hiding form fields
- Debugging and problem-solving
- Designing a solution around different business requirements

## Outcome

The tool significantly reduced the amount of manual work required to create Letters of Authorisation.

A process that could previously take a couple of hours was reduced to approximately 20 minutes, while also helping to reduce formatting errors and pushbacks caused by incorrect information.

## Note

This project was originally created to support a real business process. Company branding, addresses and any potentially sensitive or business-specific information have been removed or anonymised for this public version.
