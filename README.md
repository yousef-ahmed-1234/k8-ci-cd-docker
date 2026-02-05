# Free Kubernetes CI/CD with GitHub Actions (KIND)

This project demonstrates a **fully free CI/CD pipeline** that builds a Docker image and deploys it to **Kubernetes** using **GitHub Actions** and **KIND (Kubernetes in Docker)**.

No cloud account, no credit card, and no local Docker or Kubernetes installation are required.

---

## 🚀 What This Project Does

On every push to the `main` branch:

1. GitHub Actions builds a Docker image
2. A temporary Kubernetes cluster is created using KIND
3. The Docker image is loaded into the cluster
4. Kubernetes deploys the application
5. Application logs are printed in the GitHub Actions console

All of this runs **entirely inside GitHub Actions** and is **100% free**.

---

## 🧠 Technologies Used

- GitHub Actions (CI/CD automation)
- Docker (containerization)
- Kubernetes (container orchestration)
- KIND (Kubernetes in Docker for CI environments)
- YAML (CI/CD and Kubernetes configuration)

---



