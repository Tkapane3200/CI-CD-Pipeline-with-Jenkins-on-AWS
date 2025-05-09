# Project Structure
.
├── dockerfile
├── src/
│   └── index.html
└── README.md


# Prerequisites
```
docker build -t html-app .
```
# Running the Container
```
docker run -p 8080:80 html-app
```
After running these commands, the application will be available at ```[ http://localhost:8080] ```
