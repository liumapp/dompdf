### dompdf

> 能够支持中文的dompdf

### 支持的中文字体

* droidsans

### 使用方法

* 部署源码到服务器上

* 访问链接:

        http://站点域名/dompdf.php?base_path=www%2Ftest%2F&options[Attachment]=0&input_file=test.html&options[f]=test.pdf
   
参数解析：

base_path 文件路径 

options:

   Attachment 为0时只显示pdf不下载，为1时下载生成的pdf
   
   f则表示生成的pdf文件的名称
input_file 要进行转换的html文件名 

* 请将需要生成的html文件放在www/data目录下
