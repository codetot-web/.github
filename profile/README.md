# Code Tốt Web Development Team

## Tham gia cùng chúng tôi

Dưới đây là một số mẫu câu hỏi mà Code Tốt đặt ra với ứng viên. Chúng tôi hi vọng dù bạn biết đó là câu hỏi trong buổi phỏng vấn, thì việc đọc những nội dung này cũng sẽ giúp ích cho kiến thức bạn cần tìm hiểu và thực hành. Càng tìm hiểu và làm sát vấn đề chúng tôi nêu ra, bạn càng có cơ hội tiếp cận sâu hơn với mảng lập trình web.

Phần lớn ứng viên đạt tỷ lệ từ 75% trở lên sẽ được gia nhập đội ngũ của chúng tôi.

## Công cụ lập trình

- Bạn dùng công cụ gì để code? Nếu là VS Code, bạn thường dùng các plugin nào và tại sao?

**Git**

- Bạn sử dụng GitHub? Nếu có, bạn có biết các branch chính thường sử dụng trong các dự án không?
- Tại sao đôi khi trong GitHub nhiều người cùng làm 1 nhánh, và khi làm cùng 1 nhánh thì cách nào để luôn luôn đồng bộ code mới nhất, tránh xung đột?
- Bạn cần sửa một button để di chuyển nó từ section này sang section khác (do nghe nhầm yêu cầu từ leader team), vậy commit bạn sẽ đặt tên là gì?
- Các file nào không nên cho vào commit?
- Bạn có biết cách nào để nhánh của mình luôn cập nhật và sẵn sàng trên nhánh chính (hàng ngày) không?
- Trên máy của bạn có chứa 1 commit, nhưng chưa kịp push thì bạn `reset` nhầm về một nhánh khác. Làm thế nào để quay trở lại commit trước đây?
- Bạn có một commit hôm qua và đã cho lên live. Sau đó một số người khác cũng commit lên live. Đến hôm nay, bạn nhận ra commit của bạn bị khách hàng đổi ý và yêu cầu gỡ bỏ. Bạn sẽ làm thế nào?

## Các ngôn ngữ lập trình

**Frontend**

### HTML5

Bạn cần "vọc" HTML5 và sử dụng nó thì mới có thể trả lời các câu hỏi.

Ví dụ: 

- Làm thế nào mà HTML5 ra đời và cải tiến phiên bản HTML/XHTML?
- Những quy tắc cơ bản nào khi sử dụng các tag mới do HTML5 quy ước, chẳng hạn như "Tại sao bạn nên dùng thẻ `<section>`? Có quy tắc nào bắt buộc khi sử dụng thẻ `<section>` không?"

Link tham khảo chất lượng nhất: https://html.spec.whatwg.org/multipage/semantics.html#semantics

### CSS3

**Lý thuyết**

- Bạn có nắm được responsive mobile-first và desktop-first khác nhau như thế nào?
- Bạn có biết làm thế nào viết CSS cho nhiều trình duyệt khác nhau và tại sao cần làm thế?
- Bạn có biết làm thế nào để tránh viết `!important`?
- Tại sao nên gắn style qua CSS `class` thay vì `id`?
- Các attribute nào của CSS3 hay được sử dụng nhất so với CSS trước đó?
- Attribute nào của màu sắc được hỗ trợ từ phiên bản CSS3?
- Làm cách nào tạo hiệu ứng vòng lặp (vd di chuyển lên và xuống 10px vĩnh viễn) cho một element?
- Bạn có biết BEM CSS không? Nếu ví dụ đặt tên với 1 section cụ thể (có hình minh hoạ)

**Thực hành**

- Làm thế nào xây dựng một cấu trúc bố cục nhiều cột?
- Làm thế nào trong bố cục nhiều cột và dòng, các item đều có cùng chiều cao bất kể nội dung ngắn hay dài? (có hình minh hoạ)
- Nếu bạn đang dùng `display: grid`, vậy các trình duyệt không hỗ trợ thì bạn viết thay thế như thế nào?
- Giả sử bạn có 1 cột bên và 1 cột chính theo tỷ lệ (1/3 và 2/3), làm thế nào để tạo 1 khối luôn di chuyển theo màn hình và không ra khỏi vị trí cột bên kể cả khi kéo lên và kéo xuống quá vị trí hiển thị? (có hình minh hoạ)
- Giả sử bạn đang có 1 popup hiện ra và ẩn đi (button click mở ra, click close trong popup thì ẩn đi), vậy làm thế nào để hiệu ứng không bị giật (không dùng `display: none;`)?

**Công cụ**

- Bạn viết CSS thuần, LESS, Sass hay postCSS? Bạn dùng cách nào để chuyển SaSS/LESS sang .css?

### Javascript

Dù bạn tự hào mình biết React, Angular hay VueJS bằng cách học nó online, qua trung tâm đào tạo, Code Tốt vẫn sẽ kiểm tra tư duy xử lý bài toán Javascript thông qua những câu hỏi đơn giản.
Chúng tôi không đặt câu hỏi vào phần lý thuyết mà khai thác phần nội dung thực hành cụ thể.

**Thực hành**

- Mô tả các event sẽ xảy ra khi có 1 component `tabs` xảy ra, trong đó gồm hai kiểu là chỉ 1 item hiện và đồng thời nhiều item cùng hiện?
- Mô tả phương thức cơ bản tạo ra 1 popup khi người dùng vào 1 website sau 5 giây hiện ra, và khi click vào nút 'Đóng' thì sẽ tắt popup không hiện với người dùng này trong vòng 24 giờ.
- Mô tả cách tạo ra component `tabs`, trong đó có hiệu ứng ẩn hiện các thành phần tab content bằng animation không giật?
- Mô tả cách làm một sticky bar chứa các link menu trên cùng website, khi click vào mỗi item sẽ scroll mượt tới khu vực tương ứng có id trong trang đó. (Khó hơn) cách nào để tự động gán màu active cho item có trùng id đang chọn?

**Đang cập nhật**