# 컨테이너 인프라 구축을 위한 쿠버네티스 / 도커

[컨테이너 인프라 구축을 위한 쿠버네티스 / 도커](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791165215743)를 보고 공부합니다.  
예제는 [예제 - GitHub](https://github.com/sysnet4admin/_Book_k8sInfra)에서 보실 수 있습니다.

## Installtion
```shell
$ brew install vagrant
```

## 기본적인 명령어
기본적인 명령어입니다. 폴더를 만들고 들어간 후 `vagrant init`를 하게 되면 Vagrantfile을 만들 수 있습니다.  
Vagrantfile을 배포하고 싶다면 `vagrant up`를 사용하면 됩니다.
```sh
$ mkdir "예제"
$ cd "예제"
$ vagrant init
$ vagrant up
```
