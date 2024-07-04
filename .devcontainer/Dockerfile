# create a image for runing python 3.12 bookworkm
FROM python:3.12

# expose port used 8888
EXPOSE 8888

# map the local directory to the working directory
WORKDIR /app
COPY . /app


# install dependencies
RUN pip install -r requirements.txt
# run the server



# update pip
RUN pip install --upgrade pip
# install fastapi
RUN pip install fastapi
# install uvicorn
RUN pip install uvicorn
