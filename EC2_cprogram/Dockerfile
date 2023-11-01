# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY NFLScores.c .
# Compile the C program
RUN gcc -o NFLScores NFLScores.c
# Set the command to run when the container starts
CMD ["./NFLScores"]