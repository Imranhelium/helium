# API Usage

The hotspot miner provides a REST API for accessing real-time data and controlling miner settings.

## API Endpoints

### 1. `GET /api/miner/status`
This endpoint returns the current status of the miner.

Example:
```bash
curl -X GET http://localhost:8080/api/miner/status
