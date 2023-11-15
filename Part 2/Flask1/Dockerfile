FROM python:3.7-alpine                     # Use python3 image 
WORKDIR /app                               # Set the working directory
COPY . /app                                # Copy contents of the directory into the working directory
RUN pip install -r requirements.txt        # Install packages
EXPOSE 8080                                # Listen to port 8080
CMD ["python", "app.py"]                   # Run the flask app

# Docker build command: docker build -t docker_example_1 .
# Docker run command: docker run -d -p 5001:5000 docker_example_1