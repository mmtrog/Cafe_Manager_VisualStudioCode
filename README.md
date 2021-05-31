## Cafe Manager Project	

### 1. Giới thiệu	

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-java.svg)](https://www.java.com/)	

### 2. Hướng dẫn cài đặt môi trường 	

#### Yêu cầu:	


1.  IDE:                    Visual Studio Code
```
https://code.visualstudio.com/
```
2.  Database:               MySQL (MySQL Connector, MySQL Workbench) 
```
https://dev.mysql.com/downloads/installer/
```
*Lưu ý khi cài MySQL: Để tên user là `root` và mật khẩu là `quanghuy123`. (Nếu không thì vào trong code sửa lại ở class ConnectSQL.java cho giống tên và mật khẩu bạn đã cài cho localhost)*

3.  Library:                

**Java SE Development Kit 16:**     
```
https://www.oracle.com/java/technologies/javase-jdk16-downloads.html
```
**Date Chooser:**                    
```
https://sourceforge.net/projects/jdatechooser/files/jdatechooser/1.1.1/jdatechooser_bin_doc_1_1_1.zip/download
```
**iText PDF:**                       
```
https://jar-download.com/artifacts/com.itextpdf/itextpdf/5.5.9/source-code
```
**Java Sound:**                     
```
http://www.java2s.com/Code/Jar/j/Downloadjl101jar.htm
```


#### Các bước thiết lập	


1. Cài đặt đầy đủ MySQL và các thư viện đã yêu cầu. (Một số thư viện tải về giải nén là được)

2. Mở MySQL Workbench lên, đăng nhập vào localhost và tạo một database mới có tên là `cafe_manager`, sau đó import file `src/Mysql/cafe_manager.sql` vào database mới tạo.	

3. Trong VSC, mở folder project Cafe Manager lên, ở phần Java Project, thêm các thư viện bổ sung vào. (Chỉ ngoại trừ thư viện JDK đã đc thêm vào path trên máy tính từ lúc cài đặt còn lại phải thêm hết)

