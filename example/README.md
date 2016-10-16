ffmpeg编译
ffmpeg版本：ffmpeg-3.1.4
操作系统：Ubuntu GNU为3.2.0
原代码位置：/home/liulijun/self_study/ffmpeg-3.1.4
步骤:
1))进入到/home/liulijun/self_study/ffmpeg-3.1.4
2)./configure --prefix=/home/liulijun/self_study/ffmpeg_build/ --disable-yasm　//配置编译结果的输出目录前缀，由于系统中的yasm版本过低，故编译时diable yasm，可以通过./configure -h查看configure的配置选项
3)make && make install
4)进入到/home/liulijun/self_study/ffmpeg_build/查看编译结果

SDL:
1).下载SDL 1.x，我将源码放置于/home/liulijun/self_study/SDL1(因为该教程使用的是SDL 1.x版本)
2). 进入/home/liulijun/self_study/SDL1
3). 执行如下命令：
./configure --prefix=/home/liulijun/self_study/sdl1 --exec-prefix=/home/liulijun/self_study/sdl1 --pdfdir=/home/liulijun/self_study/sdl1/pdf --docdir=/home/liulijun/self_study/sdl1/doc --datadir=/home/liulijun/self_study/sdl1/data --htmldir=/home/liulijun/self_study/sdl1/html
//该命令的主要作用是配置编译结果的输出目录
4). 执行make && make install
5). 进入/home/liulijun/self_study/sdl1查看编译结果
