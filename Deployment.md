# Deployment 

## Build Docker

``` docker buildx build --platform linux/amd64 -t yolo . ```

## Run Docker

``` docker run -p 80:80 yolo ```

## Tag it 

``` docker tag sdoh hants/yolo ```

## Push it

``` docker push hants/yolo ```