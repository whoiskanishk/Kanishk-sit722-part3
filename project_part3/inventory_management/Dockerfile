# Your Solution
# Use Python image as base
FROM python:3.9-slim

# Set working directory in the container
WORKDIR /app

# Copy application files to the container
COPY . /app

# Install the required Python dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Set the command to run the app using uvicorn
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]
