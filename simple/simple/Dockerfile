FROM ubuntu as build 
WORKDIR /app
COPY requirements.txt .
RUN apt update && apt install -y python3 python3-pip
COPY . .

# Stage 2
FROM python:3.12-slim
WORKDIR /demo
COPY --from=build /app /demo
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python3", "core/manage.py", "runserver", "0.0.0.0:8000"]