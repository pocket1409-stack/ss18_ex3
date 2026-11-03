BoxModel gồm 4 thành phần
Margin,Boder,Content,Padding
Để xác định nguyên nhân gây đè khung, Nam thực hiện thao tác trên DevTools ( `F12`):

1.  **Select tab Elements** , use tool Chọn một phần tử (biểu **tượng** mũi tên góc trên cùng bên trái của F12) ấn vào khung **"Thông tin tài xế"** đang bị đè.
    
2.  Chuyển sang tab **Computing** ở bên phải bảng để kiểm tra biểu đồ **Box Model** .
    

### Sơ đồ Box Model minh họa phần tử lỗi (Ví dụ thực tế tại tab Computing):

    

## Phần 2. Triển khai: Đề xuất CSS mới thông tin trong DevTools Styles

Vì không thể chỉnh sửa gốc mã nguồn của tệp,Thực hiện chỉnh sửa trực tiếp trên khung**Phong cách**của DevTools để tìm thông số chuẩn xác nhất:

1.  Tại khung**Phong cách**,chọn lớp/id của thẻ HTML chứa khung "Thông tin tài sản" hoặc khung chứa tổng thể.
    
2.  Thêm hoặc điều chỉnh cách và định vị các thuộc tính:
