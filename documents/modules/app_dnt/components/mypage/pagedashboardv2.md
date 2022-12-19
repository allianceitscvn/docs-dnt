---
description: Class component extend _PageExt
---

# PageDashboardV2

Page này dùng để hiển thị:

* hỗ trợ hiển thị ở màn hình Dashboard
* các table có expand

Các props nhận vào

| Prop           | Mô tả                                                                                                                                                                                                                                                                                                                                                                             |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| renderCustomUI | <p>Sử dụng ở Expand Row của Table<br>Mục đích thêm UI giống dạng cây thư mục</p>                                                                                                                                                                                                                                                                                                  |
|                |                                                                                                                                                                                                                                                                                                                                                                                   |
| firstProps     | <p>Những properties từ parent component truyền vào gồm có:</p><ul><li>data: dữ liệu table</li><li>extra: config của table</li><li>multi: là một cờ để phân biệt là dạng multi table hay là table đơn</li><li>rowParent: nếu là table từ row expand ra thì truyền vào với mục đích reload row</li><li>fnList: truyền vào để thực hiện các functions từ parent component </li></ul> |
| colsToShow     | Danh sách các column hiển thị, sử dụng cho table ở dashboard khi ẩn column                                                                                                                                                                                                                                                                                                        |

Các functions trong component này

| Function          | Mô tả                                               |
| ----------------- | --------------------------------------------------- |
| componentDidMount | <ul><li>Thay đổi title header và browser </li></ul> |
|                   |                                                     |
|                   |                                                     |
