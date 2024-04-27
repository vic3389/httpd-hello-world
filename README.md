### 打包 Docker Image
`docker build -t web-hello-world:v1 .`

### 打上 Docker 帳號 Tag
`docker tag web-hello-world:v1 vic3389/web-hello-world:v1`

### 上傳到 Docker Hub
* 登入 Docker Hub \
`docker login`
* 上傳 Image \
`docker push vic3389/web-hello-world:v1`


### 使用 Mac with Apple silicon
