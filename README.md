# Cafe Manager Project	

## 1. Giới thiệu	

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-java.svg)](https://www.java.com/)

Đây là một dự án tham khảo từ một dự án khác cũng đi tham khảo nên tôi không hoàn toàn tạo ra nó và cũng đếch biết ai là người thực sự tạo ra đầu tiên nhưng điều tôi biết chắc chắn là nó đã được public, nhưng nếu bạn vẫn có thắc mắc có thể liên hệ với tôi.
## 2. Hướng dẫn cài đặt môi trường 	

### Yêu cầu:	


1.  IDE: Visual Studio Code
```
https://code.visualstudio.com/
```
2.  Database: MySQL (MySQL Connector, MySQL Workbench) 
```
https://dev.mysql.com/downloads/installer/
```
*Lưu ý khi cài MySQL: Để tên user là `root` và mật khẩu là `quanghuy123`. (Nếu không thì vào trong code sửa lại ở class ConnectSQL.java cho giống tên và mật khẩu bạn đã cài cho localhost)*

3.  Library:                

_Java SE Development Kit 16_     
```
https://www.oracle.com/java/technologies/javase-jdk16-downloads.html
```
_Date Chooser:_     *(Đã có trong lib)*                   
```
https://sourceforge.net/projects/jdatechooser/files/jdatechooser/1.1.1/jdatechooser_bin_doc_1_1_1.zip/download
```
_iText PDF:_        *(Đã có trong lib)*                     
```
https://jar-download.com/artifacts/com.itextpdf/itextpdf/5.5.9/source-code
```
_Java Sound:_       *(Đã có trong lib)*                    
```
http://www.java2s.com/Code/Jar/j/Downloadjl101jar.htm
```


### Các bước thiết lập	


1. Cài đặt đầy đủ MySQL và các thư viện đã yêu cầu. (Một số thư viện đã có trong thư mục `lib` và không cần thiết phải tải lại)

2. Mở MySQL Workbench lên, đăng nhập vào localhost và tạo một database mới có tên là `cafe_manager`, sau đó import file `src/Mysql/cafe_manager.sql` vào database mới tạo.	

3. Trong VSC, mở folder project Cafe Manager lên, ở phần Java Project, thêm các thư viện bổ sung vào. (Chỉ ngoại trừ thư viện JDK đã đc thêm vào path trên máy tính từ lúc cài đặt còn lại phải thêm hết)

