# Usage

Build:

```bash
git clone https://github.com/jewishmoses/maintenance.git
cd maintenance
docker build -t maintenance .
```

Start your container:

```bash
docker run --name maintenance-nginx -p 80:80 -d maintenance
```

## Requirements

If docker isn't installed you can run the following for Ubuntu:

```bash
apt update
apt install docker.io -y
```