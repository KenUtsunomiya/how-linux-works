# How Linux works

[「Linuxのしくみ 増補改訂版」](https://www.amazon.co.jp/%EF%BC%BB%E8%A9%A6%E3%81%97%E3%81%A6%E7%90%86%E8%A7%A3%EF%BC%BDLinux%E3%81%AE%E3%81%97%E3%81%8F%E3%81%BF-%E2%80%95%E5%AE%9F%E9%A8%93%E3%81%A8%E5%9B%B3%E8%A7%A3%E3%81%A7%E5%AD%A6%E3%81%B6OS%E3%80%81%E4%BB%AE%E6%83%B3%E3%83%9E%E3%82%B7%E3%83%B3%E3%80%81%E3%82%B3%E3%83%B3%E3%83%86%E3%83%8A%E3%81%AE%E5%9F%BA%E7%A4%8E%E7%9F%A5%E8%AD%98%E3%80%90%E5%A2%97%E8%A3%9C%E6%94%B9%E8%A8%82%E7%89%88%E3%80%91-%E6%AD%A6%E5%86%85-%E8%A6%9A-ebook/dp/B0BG8J5QJ1?_encoding=UTF8&sr=)の実験コード

## 実験環境の作成

```console
docker build -t how-linux-works:1 .
docker run --name how-linux-works -it how-linux-works:1
```
