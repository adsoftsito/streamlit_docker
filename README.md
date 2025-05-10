# streamlit_docker

# build image
sudo docker build -t your-user/streamlitapp .
sudo docker images

# test docker local
docker run -p 8501:8501 -d adsoft/streamlitapp

# docker login
docker logout
docker login

# docker push
docker push adsoft/streamlitapp

# deploy to https://render.com
