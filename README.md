## Những điều cầu lưu ý khi lập trình WordPress

## Lưu và hiển thị
### Lưu nội dung được submit từ client

Khi lưu nội dung được truyền từ client ( Form hoặc ajax ) thì cần phải kiểm tra kỹ. Dưới đây là các hàm có thể sử dụng :

`sanitize_email()
sanitize_file_name()
sanitize_html_class()
sanitize_key()
sanitize_meta()
sanitize_mime_type()
sanitize_option()
sanitize_sql_orderby()
sanitize_text_field()
sanitize_title()
sanitize_title_for_query()
sanitize_title_with_dashes()
sanitize_user()`

### Khi hiển thị nội dung ra html

`esc_html()
esc_url()
esc_js()
esc_attr()`