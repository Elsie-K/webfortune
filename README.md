# webfortune

## Routes 
- display the fortune `/fortune/`
- display the cow saying your message `/cowsay/<message>/`
- display the cow saying fortune `/cowfortune/`
# Docker
* build the docker image
> docker build -t karaels/webfortune .

* run docker
> docker run -dp 8003:5000 karaels/webfortune

* URL
> http://10.92.21.106:8003/

* check your container
> docker ps

* kill the docker image
> docker kill
## Local
* make a virtual environment
> python3 -m venv env
* activate the environment
> source env/bin/activate
* install stuffs that you need
> pip install -r requirements.txt
* run flask
> flask run --host=0.0.0.0 --port=8003
* URL
> http://10.92.21.106:8003/


