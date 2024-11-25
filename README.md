
# Portfolio Project

This project is a web-based portfolio designed to showcase skills, projects, and contact information. The portfolio is styled using modern web standards, including responsive design, and features dynamic elements powered by Go and Docker.

## Project Overview

The portfolio consists of the following major components:
1. **Frontend:** An HTML5, CSS3, and JavaScript-based user interface designed with a focus on aesthetics and usability.
2. **Backend:** Built using Go, the backend handles interactions such as saving data and managing server-side logic.
3. **Docker Integration:** The project is containerized using Docker for portability and ease of deployment.

## Features

- **About Me:** A section introducing the developer.
- **Projects:** A showcase of completed projects with descriptions.
- **Contact:** Details for reaching out, including email and LinkedIn.
- **IP Tracker:** Uses JavaScript to capture user IPs and save them via the backend API.

## Technologies Used

- HTML5, CSS3, and JavaScript for the frontend.
- Go for backend development.
- Docker for containerization and deployment.
- Responsive design techniques for mobile and desktop compatibility.

## File Structure

- **main.go:** The Go program handling the backend logic.
- **index.html:** The portfolio's main page.
- **Dockerfile:** Instructions for building the project Docker image.
- **go.mod/go.sum:** Dependency management files for the Go backend.

## Running the Project

### Prerequisites
- Docker
- Go installed locally

### Steps
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/sojoudian/csPortfolio.git
   ```
2. Build the Docker image:
   ```
   docker build -t portfolio-app .
   ```
3. Run the Docker container:
   ```
   docker run -p 80:80 portfolio-app
   ```
4. Open a browser and navigate to `http://localhost:80`.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute as per the license terms.

## Acknowledgments

- [Google Fonts](https://fonts.google.com/) for providing the Montserrat font.
- [Docker](https://www.docker.com/) for enabling easy deployment and containerization.
