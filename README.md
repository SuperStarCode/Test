1. Bảo vệ đưa vé cho lái xe: http://localhost:1234/log/ticking
```
{
"receive":"long",
"description":"dua ve"
}
```
2. Lái xe sẽ nhận vé http://localhost:1234/log/getticking?sender=long
```
{
"receive":"thin",
"description":"nhan ve"
}
```
3. Lái xe lấy xe http://localhost:1234/log/getCar
```
{
"receive":"long",
"description":"lay xe"
}
```
4. Lái xe trả vé cho bảo vệ http://localhost:1234/log/refundtick
```
{
"receive":"long",
"description":"lay xe"
}
```
5. Lái xe đưa tiền: http://localhost:1234/log//givemoney?reciver=thin
```
{
"receive":"long",
"description":"tra ve"
}
```
6. Bảo vệ bawtwsm giữ http://localhost:1234/log/arrest
```
{
"receive":"long",
"description":"bat giu"
}
```
