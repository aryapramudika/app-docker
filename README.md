# App Docker

## Contoh aplikasi yang sudah di bungkus dengan docker

### Python
docker build -t python-docker:latest python-flask

#### Jalanin
docker run -d --name python-docker -p 5000:5000 python-docker

#### Test
curl localhost:5000

atau

Akses di browser http://localhost:5000
