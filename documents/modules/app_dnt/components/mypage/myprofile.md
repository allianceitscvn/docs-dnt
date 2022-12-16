---
description: Class component extend _PageExt
---

# MyProfile

Chức năng: Xem và thay đổi các thông tin user đăng nhập

Các functions trong component này

| Function             | Mô tả                                                                                                                                   |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| keyScreenLang        | Key language của page                                                                                                                   |
| componentDidMount    | <ul><li>Thay đổi title header và tab</li><li>Gọi api lấy dữ liệu</li></ul>                                                              |
| requestProfile       | <ul><li>Hàm gọi api lấy dữ liệu</li><li>Cần reload lại form để apply dữ liệu mới</li></ul>                                              |
| requestUpdateChanges | <ul><li>Hàm gọi api lưu các thay đổi</li><li>Cần reload lại form để apply dữ liệu mới</li></ul>                                         |
| requestUpdatePwd     | Hàm gọi api thay đổi password                                                                                                           |
| requestUploadAvatar  | Hàm thay đổi avatar                                                                                                                     |
| onChangeTab          | Hàm chuyển tab Profile và Password                                                                                                      |
| onSaveChanges        | <p>Hàm kiểm tra thông tin để lưu thay đổi</p><ul><li>Có thay đổi gọi hàm lưu</li><li>Ngược lại show warning không có thay đổi</li></ul> |
| onUploadAvatar       | Hàm load file sau đó đi upload                                                                                                          |
| onChangePassword     | <p>Hàm kiểm tra hợp lệ của password</p><ul><li>Hợp lệ thì gọi hàm lưu</li><li>Ngược lại show warning </li></ul>                         |
| các hàm render...    | <p>Các hàm render các component</p><ul><li>renderSupport: render mô tả và hướng dẫn của màn hình</li></ul>                              |

