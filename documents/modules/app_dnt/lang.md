---
description: Setup language cho app
---

# lang

Định nghĩa bộ ngôn ngữ (mặc định là bộ en) theo loại màn hình

| File              | Mô tả                                                                                                                                                |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| common            | Dùng cho các màn hình chung, hoặc màn hình không có nhiều text                                                                                       |
| communication     | <p>Dùng ở các màn hình liên quan đến Communication</p><ul><li>Create Communication</li><li>Communication Detail</li><li>Communication View</li></ul> |
| my\_communication | Dùng cho màn hình My Communications                                                                                                                  |
| profile           | Dùng cho màn hình My Profile                                                                                                                         |
| task              | <p>Dùng cho các màn hình liên quan đến Task</p><ul><li>Create Task</li><li>Task Detail</li></ul>                                                     |

Thêm các bundles đã định nghĩa vào resource của i18next

Được gọi để khởi tạo ở config của module
