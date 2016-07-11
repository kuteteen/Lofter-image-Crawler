# Lofter-image-Crawler
Author: Sparrow 
Purpose: downloading image from www.lofter.com in every blog's page once avoiding download image one by one. 
Created: 2016-7.9 

##Introduction:
This is supportted by Python 2.7 I can not guarrentee the stablist. So far, I only use this script in Mac OS 10.11.15. User, should type the URL whose lofter blog, can either copy the main blog's url, such as "http://yudengyue.lofter.com/", or copy any other child url, such as "http://yudengyue.lofter.com/post/1d877536_b942107". The image will download in the file named as "Lofterimgdownload" of the directory where you put this .py file in. You can modify the regular expression in the function of getImg() according to the html tag in different kind of pages to fit your needs. It is just a simple edition of crawler, which can be easily modify to crawler other website. I may give more specific crawler according to specific site such as baidutieba.

#New
The new function is that there are two more mode.  Mode 1 you can download any current page like the url format as "http://yudengyue.lofter.com/?page=2&t=1466499686554". What's more, Mode 2, you can download all the images of one's blog once with type the main URL such as "http://yudengyue.lofter.com/", which is more convenient for restore all the image.
And you can just pick any postpages to download current page's images directly. It can crawle most of different css styles of lofter.

#Downloading file:
For Mac OS:
Download the Lofter_image_crawler.py to your local computer with python 2.7. Open your terminal cd into where you put this .py file. Then type "python Lofter_image_crawler.py" you can run it simply.

For Windows OS:
Latest "Lofter-image-crawler.exe.zip" file is a executable file on Windows OS, I only test on the Win8. You can just input the url of any lofter blogs directly with this .exe program.
Also you can python .py file better with python 2.7.

##If there is any problem, leave me a message.
bill0zxb@163.com

##Operation method
关于下载：
Mac OS
下载Lofter_image_crawler.py，打开terminal，进入该文件所在的目录 输入“python Lofter_image_crawler.py”

Windows
下载Lofter_image_crawler.zip，解压文件，打开exe文件即可运行

关于使用：
             ---------------------------------
                  欢迎使用乐乎图片批量下载器
             ---------------------------------
             作者：Sparrow
             目的：批量下载一个博客主域名下的所有图片
             创建：2016.7.4

输入你要下载的博客网页链接（直接在浏览器地址栏全选地址复制粘贴到"Input url:"）

1.当你复制的是单独的一片日志链接例如：
http://xxxxx.lofter.com/post/yyyyy_zzzzzz
程序会自动抓取该页的图片并自动下载到本程序所在的同一路径：
“Lofterimgdownload／xxxxx”
并根据该页的“post／（yyyyy_zzzzzz）”里的内容给图片重新命名:
yyyyy_zzzzzz_(number)

2.当你复制的是个人主页的每一页的链接例如：
http://xxxxx.lofter.com/?page=2&t=146xxxxxxxxx6
或者是：
http://xxxxx.lofter.com/
则会进入两个模式的选择：
1.仅下载当前这一页所有的日志里的图片
2.从这一页开始到最后一页所有的日志的图片
提醒：如果你要下载该博主的所有日志图片，你只需要拷贝他的首页链接，像这样：
http://xxxxx.lofter.com/

下载完图片后，程序会提示: "Do you want to quit?[Y/N]"
即你想退出吗？键入 Y 即退出，键入 N 继续使用程序。

感谢你的使用！

作者邮件：bill0zxb@163.com

