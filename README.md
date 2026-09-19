# QR Code Service

Kleiner Service, wo man nen Text eingibt und einen fertigen QR-Code bekommt.

## Lokal ausführen
```bash
uv run uvicorn app:app --reload
```

## Docker image bauen und ausführen
```bash
docker build -t qr-service .
docker run -p 8000:8000 qr-service
```