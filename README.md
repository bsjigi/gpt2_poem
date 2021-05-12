# GPT-2 poem generator
gpt-2 를 사용해서 Sonnets을 생성한다.
## Setup
```shell
pip install -r requirements.txt
```
## Generation

```
python main.py
```
## Installation
```
cd /home/ubuntu
git clone https://github.com/bsjigi/gpt2_poem/
cd gpt2_poem
```

## Run
```
docker login
docker pull bsjigi/poem-generator
docker run -it -p 80:80 bsjigi/poem-generator  
jupyter notebook --ip=0.0.0.0 --allow-root
```
