# This line tells Docker to use the official Python 3 image
FROM python:3-onbuild
# This copies all files from the current directory (on your host machine) into the [/usr/src/app] directory inside the Docker container
COPY . /usr/src/app
# Run the command: python api.py
CMD ["python", "api.py"]


