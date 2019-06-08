命令： ./nachos -q 2            功能：测试拓展线程数据结构
命令： ./nachos -q 3            功能：测试设置线程数的上限为128
命令： ./nachos -q 4            功能：测试线程状态查询命令TS()
命令： ./nachos -q 5            功能：测试优先级属性
命令： ./nachos -q 6            功能：测试优先级调度算法
命令： ./nachos -q 7            功能：测试时间片轮转调度算法
命令： ./nachos -q 8            功能：测试生产者消费者问题
命令： ./nachos -q 9            功能：测试barrier
命令： ./nachos -q 10           功能：测试读者写者问题

userprog 文件夹下：./nachos -d MS -x ../test/fibonacci 运行用户程序

./nachos -D删除磁盘
nachos -f -D   格式化磁盘并显示位图等
nachos -f -cp
./nachos -f -cp ./test/big big -p big 将文件拷贝进nachos文件系统并打印
./nachos -Q -r big 移除文件
sh test/my_test_script1.sh 显示位图
sh test/test_exercise_2-1.sh 测试添加文件属性
sh test/test_exercise_3.sh 测试扩展文件4kb的大小
sh test/test_exercise_4.sh 测试多级目录

./nachos -d S -x ../test/filesyscall 测试文件系统的系统调用
./nachos -d S -x ../test/forkyield 测试文件系统的系统调用
