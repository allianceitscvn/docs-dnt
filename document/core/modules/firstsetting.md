---
description: Module gọi đầu tiên ở mỗi màn hình
---

# firstsetting

* Dùng để gọi các setting và config của app ban đầu
* Luôn gọi ở mọi màn hình

Các funtions

| Function             | Mô tả                                                                                                                                                                                     |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| runAfterInit         | Gọi hàm gọi api FisrtSetting                                                                                                                                                              |
| getQueryFirstSetting | <p>Lấy query cho api FisrtSetting</p><ul><li>UI_LangBundles: Danh sách langBundles chung</li><li>LangCodeBrowser: Ngôn ngữ của browser user dùng nếu chưa login thì mới gửi<br></li></ul> |
| requestFirstSetting  | Hàm gọi FisrtSetting                                                                                                                                                                      |
| parseFirstSetting    | <p>Hàm xử lý data sau khi gọi api</p><ul><li>Set các config vào app</li><li>Xử lý config DefaultValues</li><li>Xử lý config LangConfig</li></ul>                                          |

