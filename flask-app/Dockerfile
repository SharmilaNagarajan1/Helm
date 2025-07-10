# Use official Python image
FROM python:3.9-slim

# Set working directory
WORKDIR /app

# Copy code and install dependencies
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

# Expose port and run app
EXPOSE 5000
CMD ["python", "app.py"]
