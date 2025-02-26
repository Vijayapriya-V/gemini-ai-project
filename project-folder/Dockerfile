# Use official Python image as base
FROM python:3.10

# Set the working directory inside the container
WORKDIR /app

# Copy project files to the container
COPY . /app

# Install dependencies
RUN pip install -r requirements_fixed.txt

# Set environment variable for API key (it will be provided during runtime)


# Run the Python script
CMD ["python", "main.py"]
