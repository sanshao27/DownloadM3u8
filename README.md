# download_m3u8

下载
----
使用命令git clone 项目地址 或者直接右上角download

如何使用
--------
url = ''<br>
test = M3u8(url)<br>
file_path = test.get_m3u8_body(url)<br>
test.download_movies(file_path)<br>

####如果下载失败movie_errors.txt文件里面将需要的参数解析出来，然后使用continue_download函数继续加载
