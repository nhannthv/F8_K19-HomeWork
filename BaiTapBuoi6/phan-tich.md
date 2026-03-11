Câu 1: id selectors có độ ưu tiên cao nhất trong Css

Câu 2: Nếu một phần tử HTML có cả h1, .title, và #main cùng set color — selector #main thắng? Vì #main là duy nhất nên chi tiết hơn?

Câu 3: Nếu thêm style="color: pink" trực tiếp vào phần tử ở Câu 2, kết quả phần tử đó có màu pink

Câu 4: theme.css có thể ghi đè base.css vì nó thêm vào sau trong html. Để ghi đè thành công thì bộ chọn (selectors) trong cả 2 file đó phải là như nhau hoặc bộ chọn trong file theme.css phải chi tiết hơn

Câu 5: có hai phần tử đều dùng class .title nhưng hiển thị màu khác nhau, vì độ ưu tiên khác nhau của nơi viết css.

Câu 6: phần tử h1 trong dashboard/index.html là có Css phức tạp nhất, vì 
        có h1, .title, #special được Style từ base.css và internal CSS
        có .title, #special còn được Style từ theme.css
        có cả inline style
       => Nhưng inline style thắng cuối cùng vì nó viết style trực tiếp bên trong thẻ