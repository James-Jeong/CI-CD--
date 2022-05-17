# CI-CD-NOTE
## 1) 구상도
![스크린샷 2022-05-18 오전 8 16 35](https://user-images.githubusercontent.com/37236920/168927320-ce2b9c64-5cb2-49e8-9949-3a3f462854b9.png)
  
![스크린샷 2022-05-13 오전 8 32 05](https://user-images.githubusercontent.com/37236920/168183762-39707b48-5199-4a23-a13e-c3d74eae972a.png)
  
## 2) CI
~~~
[Jenkins pipeline]
~~~
![스크린샷 2022-05-18 오전 8 15 51](https://user-images.githubusercontent.com/37236920/168927257-6e71ba0c-a157-40a7-9a3b-045f800e5804.png)
~~~
1. GIT > Source coude
2. MAVEN > Build to RPM file
3. DOCKER > Make a image & upload to harbor
4. HARBOR > 패키지 도커 이미지 형상 관리
~~~

## 3) CD
~~~
[Kubernetes]
~~~
![스크린샷 2022-05-18 오전 8 14 22](https://user-images.githubusercontent.com/37236920/168927135-6b790692-41b4-4a7c-b7f0-c3979d25219d.png)
~~~
1. Argo rollouts > Canary 배포 전략 사용
~~~
