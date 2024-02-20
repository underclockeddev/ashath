# ashath
another self-hosted app for tracking habits

---

## Requirements
- The latest version of Docker

## Installation
```
git clone https://github.com/underclockeddev/ashath.git
cd ashath
docker compose up -d
```

## Optional Configuration
The container internally listens on port 80 and the yml file maps that to port 8080 externally by default.
