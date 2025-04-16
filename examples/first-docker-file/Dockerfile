FROM openjdk

# Set the working directory in the image
WORKDIR /app

# Copy the files from the host file system to the image file system
COPY . /app

# Install the necessary packages
RUN javac sample.java

# Run a command to start the application
CMD ["java", "sample"]
