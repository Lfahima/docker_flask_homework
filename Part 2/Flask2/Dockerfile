FROM python:3.10-slim-buster                             # Use python3 image 
WORKDIR /app                                             # Set the working directory 
COPY . /app/                                             # Copy contents of the directory into the working directory
RUN pip install -r requirements.txt                      # Install packages 
EXPOSE 8081                                              # Listen to port 8081
CMD ["python", "app.py"]                                 # Run the flask app