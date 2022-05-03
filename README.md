# ros2-study
ROS2

## 前提とする環境

* Ubuntu 20.04.3 LTS ( on WSL2 )
* Docker 20.10.11, build dea9396

## 環境構築手順

1. dockerイメージをローカル環境へ作成
```sh
docker pull takasehideki/ros2-desktop-vnc:foxy
```

2. dockerコンテナ起動
```sh
./docker_run.sh
```
http://localhost:6080へアクセスすると、起動したコンテナ内のデスクトップ画面を確認できる

