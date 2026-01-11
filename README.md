# Simple-Html-Docker
This project demonstrates a simple HTML web page that displays the current date and time, served using a Docker container.
It is designed as a beginner-friendly example to understand how to containerize a static web application and run it using Docker CLI.
## About the Project (Detailed)
The purpose of this project is to learn the basics of Docker by containerizing a simple HTML application.
The application uses JavaScript to dynamically display the current date and time in the browser.
A lightweight Python HTTP server is used inside the Docker container to serve the HTML file.
## Technologies Used
* HTML
* JavaScript
* Docker
* Python (for HTTP server)
## :open_file_folder: Project Structure
 *SimpleHtmlDocker/
      *Dockerfile
           *src/
                *index.html
## Steps to Run the Project
1. **Clone the repository**
2. **Build the Docker image** -
   docker build -t html-server .
4. **Run the Docker container** -
   docker run -d -p 8080:8080 html-server
5. **Open in browser** -
   http://localhost:8080
## :white_check_mark: Expected Output
*The webpage displays the current date and time
*Time updates automatically every second


