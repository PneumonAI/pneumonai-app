# PneumonAI Application

C++ inference API, minimal frontend demo, and Docker deployment for PneumonAI MVP v1.

## MVP responsibilities

- Accept a chest X-ray upload through a Crow REST API.
- Run TorchScript inference with libtorch and OpenCV preprocessing.
- Return prediction, confidence, model information, heatmap, and overlay.
- Publish Swagger/OpenAPI documentation.
- Provide a minimal upload/results web interface.
- Run as one Dockerized service on one deployment server.

Linear owns roadmap planning. GitHub issues in this repository own executable application and infrastructure work.

See the [organization profile](https://github.com/PneumonAI) for project scope and resources.