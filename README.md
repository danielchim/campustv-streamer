BMKCCampusTV nginx-rtmp-win32
================

Nginx: 1.9.5  
Nginx-Rtmp-Module: 1.1.7  
openssl-1.0.1p  
pcre-8.36  
zlib-1.2.8  
# 使用方法
雙擊nginx.exe
# 簡要說明
conf/nginx.conf 為配置文件實例  
RTMP監聽 1935 端口，啟用live 和hls 兩個application  
HTTP監聽 8080 端口，
* :8080/stat 查看stream狀態  
* :8080/index.html 為一個直播播放與直播發布測試器
* :8080/vod.html 為一個支持RTMP和HLS點播的測試器

# 注意
不支持exec

# 直播測試工具 
內置了一個方便測試的pc端推流於播放的工具
