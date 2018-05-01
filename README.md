# tienlen-miennam
Game đánh bài tiến lên miền nam( 4 người ), dự tính xài nodejs với socketio cho server realtime và reactjs cho frontend
# Workflow
1. User đăng nhập, đăng kí nick
2. Sau khi login sẽ thấy được các room có sẵn hoặc tự tạo room
3. Các user join vào 1 room, đủ 4 nguời thì start
4. Quy tắc đánh như tiến lên miền anm thường, mỗi ng chơi đến lượt sẽ có 30s để đánh trc khi mất lượt
5. Reactjs frontend và socketio sẽ là 2 phần chính cho project này, react đảm nhiệm show giao diện, lưu trữ quan bài và handle các rule chơi vs socketio
6. 
7. Update 1 bộ rule và khởi tạo các giao diên cho quân bài:
## Nên lưu trữ các quan bài dưới dạng số để tiện so sánh
`3-4-5-6-7-8-9-10-11(J)-12(Q)-13(K)-14(A)-15(2 aka Heo)`

`1(Bích) < 2(Chuồn) < 3(Rô) < 4(Cơ)`
### Ex: 7 cơ === card: { name: " 7 Cơ", number: 7, symbol: 4, image: "7-4.png" }
