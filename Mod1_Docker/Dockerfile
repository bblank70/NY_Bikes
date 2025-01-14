# base image
FROM python:3.11

#imports
RUN pip install pandas

#set working directory and copy files
WORKDIR /app
COPY pipeline.py pipeline.py

#enter as bash terminal
ENTRYPOINT ["python", "pipeline.py"]