# Use the official Python image as base
FROM python:3.11-slim

# Set working directory
WORKDIR /app

# Copy the HTML file into the container
COPY src/index.html /app/index.html

# Expose port 8080
EXPOSE 8080

# Start a simple HTTP server on port 8080
CMD ["python", "-m", "http.server", "8080", "--bind", "0.0.0.0"]

