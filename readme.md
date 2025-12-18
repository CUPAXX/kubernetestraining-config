# kubernetestraining-config

This repository contains Kubernetes configuration files and manifests for three projects:

- **broadcaster**
- **hourly-image**
- **todo-apps**

## Projects

### 1. broadcaster

A service designed to broadcast messages or events to multiple clients. The Kubernetes configuration for this project typically includes Deployments, Services, and ConfigMaps to manage the broadcaster application's lifecycle and configuration.

### 2. hourly-image

A scheduled job or service that processes or generates images on an hourly basis. The Kubernetes manifests for this project may include CronJobs, PersistentVolumeClaims, and related resources to automate and manage the image processing tasks.

### 3. todo-apps

A simple to-do list application, often used for demonstration or training purposes. The Kubernetes configuration for this project includes Deployments, Services, and possibly Ingress resources to expose the application.

## Structure

```
kubernetestraining-config/
├── broadcaster/
├── hourly-image/
├── todo-apps/
└── readme.md
```

Each project directory contains the necessary Kubernetes manifests for deploying and managing the respective application.

## License

This repository is for training and demonstration purposes.
