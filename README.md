# Leaves
```
PCRに必要なプライマーを設計するツール

私は現在、遺伝子工学の研究をしています。遺伝子工学の研究ではPCRという実験法がよく使われます。PCRは特定のDNA領域を増幅することができますが、どの領域を増幅するのかを決めるのにプライマーというものが必要になります。
プライマーとなるには様々な条件があり、今まではエクセルなどを用いて手動で設計していました。そこで私は、プログラミングでこの作業を自動化するアプリケーションを作りました。

```
![スクリーンショット 2021-04-07 0 44 04](https://user-images.githubusercontent.com/81544427/113739299-9e05a700-973a-11eb-9fca-df77191689cf.png)
```
バイオインフォマティクスツール
  Alignment: DNA、タンパク質の配列の類似した領域を特定できるように並べたもの
  Blast: 類似した配列が生物内に存在するかを確かめるツール
  Conversion: 入力した配列を編集する
  Primer: PCR に必要なプライマーを設計する
```
## Project setup
### backend
```
$ cd backend
```
```
$ pip install virtualenv
```
```
$ virtualenv venv
```
```
$ source venv/bin/activate 
```
```
$ pip install -r requirements.txt
```
### frontend
```
$ cd frontend
```
```
$ npm install
```
```
$ npm run build
```
## Project start
```
$ python3 manage.py 
```
