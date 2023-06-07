# Giới thiệu HTML
HTML là ngôn ngữ đánh dấu, nó cung cấp cú pháp để đánh dấu nội dung và không chứ logic lập trình

# Ngôn ngữ đánh dấu

Hiểu đơn giản, ngôn ngữ đánh dấu sẽ giúp bạn có thể đánh dấu nội dung theo cách mang lại ý nghĩa cho nội dung đó. Hãy tưởng tượng, bạn đang sử dụng một trình soạn thảo và muốn in nghiêng một đoạn văn bản.

```
Hello <i>world</i>
```

# Siêu văn bản

Siêu văn bản là loại văn bản chứa nhiều loại nội dung khác nhau như văn bản, âm thanh, hình ảnh, video, ... và các siêu liên kết đến các siêu văn bản khác

# Cú pháp
```
<h1>This is a beautiful day!</h1>
```

# Cấu trúc file HTML

- ## Đuôi mở rộng
  Mỗi file html có phần đuôi mở rộng là ```html```. Ví dụ: ```index.html```

- ## DOCTYPE
  - Là dòng code đầu tiên cần được khai báo trong mọi file HTML
  ```<!DOCTYPE html>``` cú pháp của HTML5
  - Khai báo ```DOCTYPE``` có ý nghĩa hướng dẫn cho trình duyệt web hiểu về phiên bản HTML mà trang web đang sử dụng. Điều này đảm bảo rằng trang web của bạn được xử lý giống nhau trên nhiều trình duyệt khác nhau

- ## Thẻ html
  - Được gọi là phần tử gốc (root), là phần tử cấp cao nhất vì tất cả các phần tử khác đều là con của phần tử này
  - Thuộc tính ```lang``` được dùng để chỉ định ngôn ngữ trang web đang sử dụng, giúp các công cụ dịch ngôn ngữ, trình đọc màn hình,... có thể biết trang web đang sử dụng ngôn ngữ gì

- ## Thẻ head
  - là thẻ con của thẻ html
  - là nơi chứa các thẻ meta

- ## Thẻ body
  - là thẻ con của thẻ html
  - là nơi chứa nội dung website

- ## Thẻ meta
  - Cung cấp thêm thông tin và dữ liệu cho trang web
  - Được viết trong thẻ head
  - Thẻ tự đóng (self-closing tag)
  - ### meta charset 
    khai báo đầu tiên trong thẻ head
    ```UTF-8``` phổ biến nhất có tác dụng hỗ trợ hiển thị các ký tự nằm ngoài khoảng từ A - Z
  - ### meta title
    ```<title>HTML & CSS</title>```
    Dùng để cung cấp tiêu đề cho trình duyệt và các công cụ tìm kiếm
  - ### meta viewport
    width=device-width
    initial-scale=1.0 giữ đúng tỉ lệ của trang web
  - ### meta Open Graph (OG)
    Là các thẻ được trình thu thập nội dung của Facebook sử dụng, nhằm lấy thông tin trang web phục vụ việc hiển thị khi trang web được chia sẻ trên mạng xã hội này 
    - property
    - content
    ```
    <meta
      property="og:url"
      content="https://fullstack.edu.vn/blog/tong-hop-cac-san-pham-cua-hoc-vien-tai-f8.html"
    />
    <meta property="og:type" content="article" />
    <meta property="og:title" content="Tổng hợp các sản phẩm của học viên tại F8 | by Sơn Đặng | F8" />
    <meta
      property="og:description"
      content="Bài viết này nhằm tổng hợp lại các dự án mà học viên F8 đã hoàn thành và chia sẻ trên nhóm Học lập trình web F8. Các dự án dưới..."
    />
    <meta
      property="og:image"
      content="https://files.fullstack.edu.vn/f8-prod/blog_posts/65/6139fe28a9844.png"
    />
    ```
# Sử dụng HTML boilerplate
  - boilerplate là những đoạn code được tiêu chuẩn hóa và tái sử dụng ở nhiều nơi mà ít khi có sự thay đổi
  - Sử dụng Emmet

# Các thẻ HTML thông dụng
  - ```h1 - h6``` 
    - heading
    - Các tiêu đề chính, phụ
  - ```p```
    - paragraph 
    - đoạn văn bản
  - ```b, i, u```
    - bold - italic - underline
  - ```a```
    - anchor 
    - đường link truy cập
  - ```img```
    - self-closing tag
  - ```ul, li```
    - Để hiện thị giao diện danh sách
    - Danh dách không có thứ tự
  - ```ol, li```
    - Để hiện thị giao diện danh sách
    - Danh dách có thứ tự

# Thuộc tính trong HTML (attribute)
  - Thuộc tính (attribute) được sử dụng để bổ sung thêm thông tin cho các thẻ HTML
  - Có dạng key="value"
  - ## Thuộc tính toàn cục
    - Được sử dụng ở tất cả các thẻ HTML
    - ```lang``` thuộc tính có tính thừa kế
    - ```hidden``` thuộc tính chỉ có key, các thẻ có thuộc tính hidden sẽ được ẩn khỏi giao diện web
    - ```title``` Đây là thuộc tính bổ sung thông tin cho một thẻ HTML, nội dung của thuộc tính này sẽ hiển thị khi bạn đưa con trỏ chuột vào phần nội dung của nó.