##  Docker Setup

This project is containerized using Docker.

## Steps:
1. Build Docker image:
   docker build -t my-website .

2. Run container:
   docker run -d -p 8080:80 my-website

3. Access:
   http://13.212.96.115:8080
