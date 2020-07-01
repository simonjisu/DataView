# voila-example

You can see how to using ipython `widgets` packages in Google Colaboratory, otherwise see how to render it by voila at local machine.

At some documents, you will need Nanum Font to see korean fonts("네이버"의 나눔바른고딕 TTF: [link](https://hangeul.naver.com/font))

## Quick Start with Colab

|Notebook|Colab link|
|--|--|
|01_Traffic.ipynb| Not ready for it|
|02_Test Report for model Analysis.ipynb| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/simonjisu/voila-example/blob/master/02_Test%20Report%20for%20model%20Analysis.ipynb)|


## Needed Packages: 

In the terminal, type like below.

```
$ pip install numpy
$ pip install matplotlib
$ pip install pandas
$ pip install voila
```

## How to Start 1

In the terminal, type like below.

```
$ jupyter notebook
```

Click the "Voila" button in your jupyter notebook.

<img src="https://drive.google.com/uc?id=1sK-6PYqrUodwHHym8717utRZb3PJhj1Z" width="640" height="100">

## How to Start 2

In the terminal, type like below.

```
$ voila 01_Traffic.ipynb
```


## Data Description

* `alldata_groupby.csv` >`01_Traffic.ipynb` 한국 도로공사 공동데이텉 포털([http://data.ex.co.kr/](http://data.ex.co.kr/))의 데이터 활용
* `result.csv` > `02_Test Report for model Analysis.ipynb`