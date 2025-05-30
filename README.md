# E-LEARNING-PLATFORM-UI

*COMPANY*: CODTECH IT SOLUTIONS 

*NAME*: JANAPATI SANDHYA 

*INTERN ID*:CT04DL793

*DOMAIN*: FRONT END DEVELOPMENT 

*DURATION*:4WEEKS

*MENTOR*:NEELA SANTOSH

##Description: E-learning Platform using React and Tailwind CSS

This project is a simple E-learning platform built using React and styled with Tailwind CSS. The purpose of this application is to present a list of online courses, each featuring an embedded video, a visual progress bar, and a call-to-action button that encourages users to continue learning. The platform focuses on providing an interactive and clean interface that is also responsive for various screen sizes.

The structure begins with a standard HTML5 document. The project includes external scripts for React and ReactDOM (version 17) loaded via CDNs. Babel is used in-browser to compile JSX, allowing React components to be written directly in the HTML file. Tailwind CSS is included via CDN for utility-based styling. Additionally, a small custom CSS block is defined to ensure that embedded YouTube videos maintain a 16:9 aspect ratio, keeping the layout consistent and responsive.

The main content is rendered into a div with the ID root, styled with Tailwind classes to center the content and provide padding. All application logic is written in JSX inside a <script type="text/babel"> tag. The core data consists of an array named courses, where each object represents a course with an id, title, progress, and videoUrl. This static data serves as the foundation for the dynamic rendering of course content.

A functional React component named CourseCard is used to display each individual course. This component receives a course object as a prop and renders a styled card. Each card includes the course title, an embedded YouTube video using an <iframe>, a progress bar, and a “Continue” button. The progress bar visually indicates how much of the course has been completed, using a colored div with a dynamic width based on the progress percentage.

The main App component renders the platform’s header and iterates over the courses array using the .map() function. It passes each course to the CourseCard component and assigns a unique key for React’s reconciliation process. The entire app is then rendered into the root element using ReactDOM.render().

Styling is handled extensively with Tailwind CSS, giving the application a modern look. Features like shadows, rounded corners, spacing, and responsive padding are applied to ensure a clean and professional interface. The embedded videos are fully responsive due to the custom CSS defined for the .video-container class.

This project showcases the integration of component-based development using React with rapid UI design using Tailwind CSS. Although the application currently uses static data, it is structured in a way that allows for easy expansion. Features such as API integration, user authentication, dynamic progress tracking, and personalized dashboards can be added in the future to enhance functionality.

Overall, this E-learning platform serves as a foundational project for building modern, user-friendly educational web applications. It emphasizes modularity, responsiveness, and ease of use, making it a strong example of combining React and Tailwind CSS for interactive front-end development.

#OUTPUT

![Image](https://github.com/user-attachments/assets/4a5715e8-ee2d-4122-bba0-0c9a619a725c)


