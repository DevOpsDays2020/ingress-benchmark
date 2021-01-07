# Ingress Benchmark


## Ingress Nginx和原生Nginx的性能

使用wrk测试Ingress Nginx和原生Nginx的性能

###  说明
- nginx-deployment.yaml: backend web server，作为后端服务，用于压测
- nginx-proxy.yaml: proxy server，作为代理服务器，用于对比ingress-nginx

其中nginx-deployment.yaml中的Ingress使用ingress-nginx组件代理。

性能测试见文章：[ingress-nginx 性能压测](https://amuguelove.github.io/post/ingress-nginx-benchmark)

## 不同Ingress Controller的性能

kubernetes ingress vs nginx ingress vs traefik ingress

