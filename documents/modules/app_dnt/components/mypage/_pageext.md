---
description: Class component chung, các page khác sẽ extend vào
---

# \_PageExt

Các page extends vào đây khi:

* thuộc kiểu page chung (có các xử lý giống với core page)
* cần sử dụng những function với những page khác

Core page gồm những đặc điểm cơ bản sau:

* Cần gọi List và Options
* Có thể có filter và phân trang server

Các function có trong component

| Function             | Mô tả                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| componentWillUnmount | Emit Event remove event lắng nghe reload list                                                                                                                                                                                                                                                                                                                                                                                             |
| componentDidMount    | <ul><li>Thay đổi header ở header và title tab browser</li><li>Gọi componentDidMount của page đang extend</li><li>Khởi tạo Emit Event lắng nghe reload list</li></ul>                                                                                                                                                                                                                                                                      |
| initReloadListener   | Hàm khởi tạo event lắng nghe reload list                                                                                                                                                                                                                                                                                                                                                                                                  |
| myComponentDidMount  | Các xử lý trong componentDidmount của các page extend vào, các page đó sẽ overwrite lại hàm này                                                                                                                                                                                                                                                                                                                                           |
| forceReloadList      | Hàm bắt buộc reload list lại, khi event reload list gọi, các page extend sẽ overwrite lại                                                                                                                                                                                                                                                                                                                                                 |
| changeTitle          | Hàm thay đổi title page và header                                                                                                                                                                                                                                                                                                                                                                                                         |
| các hàm get...       | Hỗ trợ lấy config từ configPage                                                                                                                                                                                                                                                                                                                                                                                                           |
| các hàm render...    | Hàm render các component các page extend  có thể dùng chung                                                                                                                                                                                                                                                                                                                                                                               |
| \_sharedFnList       | <p>Các function các page extend dùng chung</p><ul><li>renderFilter: Hiển thị bộ lọc dữ liệu (thường dùng các màn hình có table)</li><li>renderEmpty: Hiển thị message khi không có dữ liệu</li><li>renderBottomToast: Hiển thị message ở góc trái phía dưới màn hình</li><li>renderButtonHeader: Hiển thị các button chức năng (thường là các chức năng export)</li><li>renderSupport: Hiển thị mô tả và hướng dẫn của màn hình</li></ul> |
|                      |                                                                                                                                                                                                                                                                                                                                                                                                                                           |

