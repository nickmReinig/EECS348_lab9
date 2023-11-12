# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY nflScore.c .
# Compile the C program
RUN gcc -o nflScore nflScore.c
# Set the command to run when the container starts
CMD ["./nflScore"]