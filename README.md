# AWS Workshop Template - Cloud Journey/AWS Study Group

Các thông tin cần chỉnh sửa trong các file:

**config.toml**

```toml
baseURL=<Thêm địa chỉ và đường dẫn>

[params]
  author = "<Thêm e-mail hoặc tên>"
[Languages]
[Languages.xx]
title = "AWS WORKSHOP" # Sửa lại tên theo ý muốn
```

**layouts/partials/menu-footer.html**

```html
[...]
<b> Team </b> <br>
<i> <a href="<Thay bằng url bạn muốn>"  style="color:orange"> Thay bằng tên bạn </a> <br>
[...]
```