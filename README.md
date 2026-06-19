# myapp

Simple Python web application for the LMS deployment course.

## Run locally

```powershell
python app.py
```

Open http://localhost:8000.

## Docker

```powershell
docker build -t myapp:test .
docker run -p 8000:8000 myapp:test
```
