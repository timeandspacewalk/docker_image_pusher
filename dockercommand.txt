docker run -d --name autman --restart always --network=host -v /path/to/your/directory:/autMan hdbjlizhe/autman:latest
-d 表示后台运行容器。
--name autman 为容器指定一个名称。
--restart always 表示容器退出时总是尝试重启。
--network=host 表示使用宿主机的网络堆栈。
-v /path/to/your/directory:/autMan 表示将宿机上的目录挂载到容器内的 /autMan 目录，您可以根据需要更改宿机上的路径。
hdbjlizhe/autman:latest 是autMan的Docker镜像名和标签。
