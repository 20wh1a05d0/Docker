# Use a lightweight base image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /home/data

# Copy the text files and Python script to the container
COPY IF.txt /home/data/
COPY AlwaysRememberUsThisWay.txt /home/data/
COPY scripts.py /home/data/

# Install Python dependencies (if needed)
#RUN pip install --no-cache-dir -r requirements.txt

# Run the Python script when the container starts
CMD ["python3", "/home/data/scripts.py"]