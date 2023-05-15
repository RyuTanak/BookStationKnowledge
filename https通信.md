# https通信について  

BookStationでnode.jsを起動した後に  
https://localhost:8080/public/pages/signin.html  
で接続したときに以下の画面が表示される  
![img](./img/2.png)  

これって何？  

# https通信とは  

以下のサイトを読んでみた。  
https://wa3.i-3-i.info/word17016.html  

通信プロトコル→通信するときのお約束  
http→ホームページのファイルを受け渡しする時のお約束（通信プロトコル）  
ssl→インターネット上で暗号化通信するときのお約束（通信プロトコル）  
https→httpとsslが合体したもの  

## 暗号化通信の流れ  
sslは暗号化通信するときの流れであることが分かった。  
では、暗号化通信とはどのように行われるのか  
