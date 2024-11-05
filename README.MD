# Prometheus Dashboard

A simple dashboard for monitoring Prometheus metrics using Grafana Cloud visualization.

## Setup

### Prerequisites
- Docker
- Docker Compose

### Local Development
1. Clone the repository:
```bash
git clone https://github.com/yourusername/prometheus-dashboard.git
cd prometheus-dashboard
```

2. Build and run the container:
```bash
docker-compose up -d
```

3. Access the dashboard at `http://localhost:80`

### Production Deployment
1. Pull the repository on your Ubuntu server:
```bash
git clone https://github.com/yourusername/prometheus-dashboard.git
cd prometheus-dashboard
```

2. Start the service:
```bash
docker-compose up -d
```

## Configuration

Update the Grafana embed codes in `src/index.html` to connect to your Grafana Cloud instance.

## Development

To make changes:
1. Modify files locally
2. Test changes with `docker-compose up -d --build`
3. Commit and push changes
4. Pull and rebuild on your server

## License

MIT