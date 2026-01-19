1. Personal Information

Name: Varun

UID: 24BCY70066

Group: 24BCY - 3(A)

2. Title of the Experiment

Develop an Admin Dashboard with CSS Grid Layout and Dynamic Theme Switching

3. Defined Approach

To develop the admin dashboard, a structured and modular approach was followed. First, the basic layout of the dashboard was created using HTML5 semantic elements such as header, aside, and section to ensure clarity and accessibility.

Next, CSS Grid layout was implemented to divide the dashboard into multiple sections including navigation, analytics, users, and settings. The grid-template-areas property was used to clearly define the placement of each component, making the layout responsive and easy to manage.

For theme management, CSS variables were defined to store color values for background, text, borders, and cards. Two themes were created: a default dark theme and a light theme, which dynamically change the appearance of the dashboard.

JavaScript was used to implement the theme toggle functionality. On clicking the theme switch button, a CSS class was added or removed from the body element to switch between dark and light modes.

Finally, localStorage was used to store the user’s theme preference so that the selected theme persists even after refreshing or reopening the browser. This ensures a consistent user experience.
