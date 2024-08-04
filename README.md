
# Job Portal Project

The Job Portal is a web application designed to connect job seekers with recruiters. Job seekers can search for jobs using various filters, apply for jobs, and update their profiles. Recruiters can post job listings and view details of applicants.


## Features
Job Seeker

- Search Jobs: Filter jobs based on criteria such as location, job type, and industry.

- Apply for Jobs: Submit applications for job listings.
- Profile Management: Update personal and professional information.
  Recruiter
- Post Jobs: Create and manage job listings.
- View Applicants: Access details of job seekers who have applied for positions.


## Technology Used
- Backend: Java, Spring Boot
- Frontend: Thymeleaf, Bootstrap, jQuery, HTML
- Database: MySQL
## Installation

1. Clone the repository:

```bash
  git clone https://github.com/divyanshugupta29/Job-Portal.git
  cd Job-Portal
```

2. Set up the MySQL database:
- Create a database named job_portal.
- Update the database configuration in application.properties.

3. Build and run the application:
```bash
  ./mvnw spring-boot:run
```

4. Access the application: Open your browser and navigate to http://localhost:8080