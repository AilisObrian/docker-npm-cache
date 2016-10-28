# NPM 너무 느려!!!!!!

npm서버를 직접 docker로 띄웁시다!

```bash
$ docker-compose up -d
$ mv ~/.npmrc ~/.npmrc.backup  # 혹시모르니까?
$ cp npmrc ~/.npmrc
```
