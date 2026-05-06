gọi vào endpoint read file là [/file/download-text](http://192.168.1.10:1704//file/download-text?filepath=%2Fvar%2Flib%2FApiGateway%2FAi_Training%2FScan.md)

giải thích: 
- 192.168.1.10 là IP server
- File là /var/lib/ApiGateway/Ai_Training/Scan.md

response cấu trúc như sau:
{
  "ok": true,
  "data": "nội dung file"
}