sh configure

+ linux下gcc编程10-clion编译调试nginx:<https://blog.csdn.net/liaomin416100569/article/details/105127557/>

1. cmake复制进nginx/auto里边
2. 将nginx/configure中的. auto/make上加上. auto/cmake
3.  -c  /Users/kingsonwu/Personal/C-source-code/nginx-1.16.1/conf/nginx.conf

+ mac ide中每sudo权限的问题
    - sudo chown kingsonwu:staff  /usr/local/nginx/logs
    - 端口改成1234,80端口要sudo
    - curl localhost:1234