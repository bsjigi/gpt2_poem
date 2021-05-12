# GPT-2 poem generator
gpt-2 를 사용해서 Sonnets을 생성한다.

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
docker run -p 80:80 -d bsjigi/poem-generator  
```
