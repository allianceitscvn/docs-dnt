---
description: Thư mục config chung của app
---

# App

<details>

<summary>App</summary>

Gọi tới routes của app&#x20;

</details>

<details>

<summary>AppConfig</summary>

Nơi cấu hình  và khởi tạo các modules của 1 app

<pre><code><strong>appInfo: {
</strong>    title: title chính của website,
    appName: cấu hình tên app (dùng để gửi lên server mỗi lần gọi api),
    home: cấu hình đường dẫn trang home,
    acceptedFiles: cấu hình các loại file được phép upload (dùng ở các vùng liên quan đến upload file, document)
    acceptedFilesNotIncludeImg: cấu hình các loại file được phép upload (không tính loại ảnh, chỉ dùng ở chức năng upload file ở vùng Editor)
    GoogleClientId: cấu hình id của google để login
    GAId: cấu hình id của Google Analytics,
    pathLogo: cấu hình đường dẫn ảnh logo ở màn hình login,
    pathMainLogo: cấu hình đường dẫn ảnh logo mặc định ở header và sidebar,
    useLogoServer: cấu hình có sử dụng logo lấy từ server không,
    loginBannerImages: cấu hình slide banner ở màn hình login,
    isCustomLang: cấu hình có sử dụng bộ language tự custom hay không,
    defaultLang: cấu hình ngôn ngữ mặc định,
    defaultLangBundles: cấu hình các bộ text dùng chung,
    currentVersionLang: phiên bản language,
    supportSubdomainConfig: cấu hình có hỗ trợ sub domain không (dùng cho release),
    openDetailInModal: cấu hình mở detail ở dạng popup hay không,
    targetOpenUrlDetail: cấu hình mở link tới các màn hình detail (mở tab mới hay là mở tab hiện tại),
    hasSignalR: cấu hình có sử dụng SignalR hay không
    signalRHub: cấu hình hub link của SignalR,
    signalRKey: cấu hình key của SignalR,
 },
configApi: {
    baseUrl: cấu hình đường dẫn domain api,
    fnLogout: hàm thực hiện logout,
 },
configI18n: cấu hình mặc định cho bộ language
configAuth: cấu hình các hàm cần thiết cần dùng liên quan đến authorization
fnList: cấu hình, định nghĩa các hàm dùng chung toàn website
modules: mảng các modules để khởi tạo
UIAppConfig: các cấu hình chung (vd: các dạng format, màu sắc) server có thể replace nếu muốn
</code></pre>

</details>

<details>

<summary>Khác</summary>

Nơi khai báo các function và state sử dụng cho toàn app (sử dụng redux-thunk) cho các chức năng như login, notify, sidebar

Bao gồm các file\
\- App.actions\
\- App.constants\
\- App.thunk\
\- App.reducer

</details>
