# Mobile Technical Assessment

Create an Android app that displays coronavirus statistics using the provided API [here](https://covid-api.com/api/).

You must use Kotlin or Kotlin Multiplatform for your implementation.

## Functional Requirements
- Users should be able to view global statistics (confirmed cases, deaths, fatality rate percentage).
  - Endpoint for Global statistics: https://covid-api.com/api/reports/total
- Users should be able to view a list of statistics per country (confirmed cases, deaths, fatality rate percentage).
  - Endpoint to get countries ISO codes: https://covid-api.com/api/regions
  - Endpoint for statistics per country: https://covid-api.com/api/reports/total?iso={ISO_CODE}
    - E.g: https://covid-api.com/api/reports/total?iso=AUS
- Users should be able to search for specific countries and see its statistics.
- Please don't hesitate to utilise third-party libraries to accelerate your development process, but ensure that you can provide a valid rationale for their inclusion.

## UI/Design Requirements
The design and layout of the app is up to you. We encourage you to showcase your creativity in creating a user-friendly and visually appealing UI.

## What We Will Be Looking For
Through this assessment, we want to evaluate your approach in the following areas:

- **Code Quality:**
    - Utilise the DRY (Don't Repeat Yourself) principle.
    - Implement unit tests for your code.
    - Apply separation of concerns and adhere to good design patterns.
- **Code Standards:**
    - Ensure consistency in coding style and patterns.
    - Follow industry best practices and coding conventions.
- **Code Robustness:**
    - Implement error handling mechanisms.
    - Ensure graceful failure of the app in exceptional scenarios.
- **App Performance:**
    - Optimise your code for improved performance.
- **UX Design Creativity:**
    - Present data in a user-friendly and intuitive manner.


## Submission
Please follow these instructions for submitting your assessment:

- Create a repository on GitHub or Bitbucket to host your code.
- Include a README file in the repository with instructions on how to build and run your app.
- Please also supply a video or gif showcasing your App.
- Email the URL of your repository back to me.

*Good luck and Happy Coding!*