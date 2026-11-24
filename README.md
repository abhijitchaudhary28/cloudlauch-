# CloudLaunch

A beginner-friendly static website project for learning web development, Docker containerization and cloud deployment.

## Files
- `index.html` — page structure
- `style.css` — responsive styling
- `script.js` — menu and footer interactions
- `Dockerfile` — starter container image configuration

## Run locally
Open `index.html` in your browser.

## Build and run with Docker (after Docker is installed)
```bash
docker build -t cloudlaunch .
docker run -d -p 8080:80 --name cloudlaunch-web cloudlaunch
```
Then open http://localhost:8080

Stop and remove the container:
```bash
docker stop cloudlaunch-web
docker rm cloudlaunch-web
```
