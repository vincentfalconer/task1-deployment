# Use Python 3.6 or later as a base image
FROM python:3.10-slim
# Copy contents into image
COPY app.py .
COPY requirements.txt .
# Install pip dependencies from requirements
RUN pip install --no-cache-dir -r requirements.txt
# Set YOUR_NAME environment variable
ENV YOUR_NAME="Vince Flock"
# Expose the correct port
EXPOSE 5500
# Create an entrypoint
ENTRYPOINT ["python", "app.py"]
