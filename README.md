# docker-jupyter
Jupyter Lab+Hub


# How to install
mkdir Docker -p

cd Docker

git clone https://github.com/winuthayanon/docker-jupyter

cd docker-jupyter

# Edit docker-compose.yml file
vi docker-compose.yml

# Start
docker-compose up -d

Go to https://jupyter.domain.com
Default
User=scrna
Pass=Pass4scrna

After login you can change password by open the Terminal and type command

passwd

# Stop
docker-compose down
