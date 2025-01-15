# Microservices Project with Docker and Flask

This project demonstrates a simple microservices-based architecture using **Docker**, **Docker Compose**, and **Flask**. It consists of five independent services, each running as a containerized web application. This is a practical example for learning how to build, deploy, and manage microservices using Docker.

---

## Features
- Five standalone Flask-based services.
- Containerized using lightweight **Docker** images.
- Managed and orchestrated with **Docker Compose**.
- Easy setup with clear, step-by-step instructions.

---

## Prerequisites
- **Docker**: Install from [here](https://www.docker.com/).
- **Docker Compose**: Included with Docker Desktop or install from [here](https://docs.docker.com/compose/).

---

## Installation and Usage

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/microservices-project.git
cd microservices-project
```

### 2. Build and Start the Services
```bash
docker-compose up --build
```

### 3. Access the Services
Open your browser and navigate to the following URLs:
- Service 1: [http://localhost:5000](http://localhost:5000)
- Service 2: [http://localhost:5001](http://localhost:5001)
- Service 3: [http://localhost:5002](http://localhost:5002)
- Service 4: [http://localhost:5003](http://localhost:5003)
- Service 5: [http://localhost:5004](http://localhost:5004)

### 4. Stop the Services
Press `Ctrl+C` in the terminal to stop the services, then run:
```bash
docker-compose down
```

---

## Project Structure
```plaintext
microservices-project/
├── service1/
│   ├── app.py              # Flask application for Service 1
│   ├── requirements.txt    # Python dependencies for Service 1
│   └── Dockerfile          # Dockerfile for Service 1
├── service2/
│   ├── app.py              # Flask application for Service 2
│   ├── requirements.txt    # Python dependencies for Service 2
│   └── Dockerfile          # Dockerfile for Service 2
├── service3/
│   ├── app.py              # Flask application for Service 3
│   ├── requirements.txt    # Python dependencies for Service 3
│   └── Dockerfile          # Dockerfile for Service 3
├── service4/
│   ├── app.py              # Flask application for Service 4
│   ├── requirements.txt    # Python dependencies for Service 4
│   └── Dockerfile          # Dockerfile for Service 4
├── service5/
│   ├── app.py              # Flask application for Service 5
│   ├── requirements.txt    # Python dependencies for Service 5
│   └── Dockerfile          # Dockerfile for Service 5
├── docker-compose.yml       # Compose file for running all services
└── README.md                # Documentation file
```

---

## How It Works
- Each service is a Flask web app that responds with a simple message.
- The services are containerized using Docker.
- **Docker Compose** orchestrates the services, mapping each service to a unique port.
- Running `docker-compose up --build` starts all services simultaneously.

---

## Customization
- To modify a service, edit the corresponding `app.py` file in its directory.
- Add new dependencies to the `requirements.txt` file for the service.
- Rebuild the project after making changes:
  ```bash
  docker-compose up --build
  ```

---

## Contributing
Contributions are welcome! If you’d like to contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature-name"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Copy and paste this content into your `README.md` file, and you're good to go! 😊
