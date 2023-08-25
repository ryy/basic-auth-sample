# basic-auth-sample
This repository provides a sample implementation of Basic Authentication. Additionally, it includes a simple demonstration using JavaScript to display input information from a login form as an alert.

## Prerequisites
Docker and Docker Compose installed

## Setup
1. Clone the repository:
```bash
git clone https://github.com/your-username/basic-auth-sample.git
cd basic-auth-sample
```

2. Launch the services using Docker Compose:
```bash
docker-compose up
```

3. Open `http://localhost:8080` in your browser. Confirm the display of the Basic Authentication dialog. Log in using the provided username and password.

4. Upon entering the correct credentials, a simple login form should appear. Fill in the ID and password, click the login button, and an alert should display with your input.
