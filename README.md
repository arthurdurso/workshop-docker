# Workshop de Docker

Para conseguir rodar o código, siga os seguintes passos no Git Bash:

'''bash
git clone https://github.com/arthurdurso/workshop-docker.git
cd workshop-docker
'''

docker build -t first-image .
docker run -d -p 8501:8501 --name first-container first-image

- Ainda é possível rodar esse projeto no Render.