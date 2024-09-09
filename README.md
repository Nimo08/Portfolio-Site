## Description
This project is a personal portfolio website designed to showcase my software development projects, particularly focusing on back-end skills integrated with front-end technologies. The site will provide a dynamic and interactive user experience using Django, Django REST Framework, and HTMX.

## Features
- **Project Display**: Showcase individual projects with detailed descriptions, tech stack, and links to live demos or repositories.
- **Dynamic Content Loading**: Use HTMX to load project details and other content without full-page reloads.
- **API Integration**: Serve project data via RESTful APIs using Django REST Framework.
- **Responsive Design**: Ensure the site is accessible and visually appealing on both desktop and mobile devices.

## Technologies Used
- **Backend**: Django, Django REST Framework
- **Frontend**: HTMX, HTML, CSS, JavaScript
- **Database**: PostgreSQL (or SQLite for development)
- **Deployment**: To be determined.

## Setup and Installation
1. Clone the repository: `git clone <link to repo>`
2. Navigate to the project directory: `cd portfolio-site`
3. Install dependencies: `pip install -r requirements.txt`
4. Set up the database: `python manage.py migrate`
5. Run the development server: `python manage.py runserver`

## Usage
Once the project is set up, navigate to `http://localhost:8000` to view the site. You can explore the projects and other content as intended.

## Future Enhancements
- **Blog Section**: Add a blog to share articles and tutorials.
- **Contact Form**: Implement a contact form with email functionality.
- **Project Filters**: Add filters to allow users to sort projects by technology or date.
