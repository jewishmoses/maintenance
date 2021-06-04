# Usage

Build:

```bash
docker build -t maintenance .
```

Start your container:

```bash
docker run --name maintenance-nginx -p 80:80 -d maintenance
```