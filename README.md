<h1> <a href="https://core.today"><img align="right" src="https://yt3.ggpht.com/ytc/AAUvwnh2lB4_C2JCESnuI17W0klPo4P5qF0gVPSZ0_28=s900-c-k-c0x00ffffff-no-rj" width="180px"></a> Word2Vec Model </h1>

한국어 Word2Vec 모델입니다.

## Installation
모델은 아래와 같이 다운로드 할 수 있습니다.
```sh
$ git clone https://github.com/CoreDotToday/word2vec.git
$ cd word2vec
$ python utils.py download
```

## Usage
모델은 [gensim](https://github.com/RaRe-Technologies/gensim)을 사용해서 로드할 수 있습니다.
```sh
$ python utils.py demo --model model.bin
Loading model...
Model loaded
...
````
