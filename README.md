## ip lookup
- 用第三方api取得ip資訊和把ip經緯度標在地圖上
- 可以打包成docker image
- github action 配合 docker compose 自動部屬
```
cd ip-lookup
docker build -t lookup .
docker run lookup
```
visit 127.0.0.1:5000
