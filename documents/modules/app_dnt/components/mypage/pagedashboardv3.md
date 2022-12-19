---
description: Class component extend _PageExt
---

# PageDashboardV3

Sử dụng cho trang home

Các functions trong component này

| Function          | Mô tả                                                                                                            |
| ----------------- | ---------------------------------------------------------------------------------------------------------------- |
| componentDidMount | <ul><li>Thay đổi title header và tab browser</li><li>Gọi api lấy data</li><li>Khởi tạo reload listener</li></ul> |
| forceReloadList   | Overwrite từ PageExt, gọi reload data không show loading                                                         |
| requestData       | Hàm gọi api lấy list data                                                                                        |
| renderList        | Hàm render danh sách các MyUI từ data                                                                            |

