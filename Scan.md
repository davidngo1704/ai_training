gọi vào endpoint scan file là [/file/scan](http://192.168.1.10:1704/file/scan?filepath=%2Fvar%2Flib%2FApiGateway)

giải thích: 
- 192.168.1.10 là IP server
- api trên lấy cây thư mục tại folder /var/lib/ApiGateway

response cấu trúc như sau:
{
  "ok": true,
  "data": [
    {
      "key": "/var/lib/ApiGateway/dai",
      "label": "dai",
      "type": "folder",
      "parentKey": "/var/lib/ApiGateway"
    }
  ]
}