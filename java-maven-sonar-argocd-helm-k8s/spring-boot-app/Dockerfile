FROM maven:3.8-openjdk-17-slim

# Install Docker CLI
RUN apt-get update && apt-get install -y docker.io && rm -rf /var/lib/apt/lists/*

# Set user to root to allow Docker access
USER root

# Keep container running
CMD ["tail", "-f", "/dev/null"]
