# serive pydevcontainer
FROM python:3.12-bookworm
WORKDIR /app
COPY . .
RUN pip install --upgrade pip
RUN pip install fastapi
RUN pip install uvicorn
EXPOSE 8888
CMD ["sleep", "infinity"]
