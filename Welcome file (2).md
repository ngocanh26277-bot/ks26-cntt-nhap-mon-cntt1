### PHẦN 1: PHÂN TÍCH LỖI

1.  **Vì sao Auto TOC rỗng?**
    
    -   **Cơ chế:** Word chỉ tạo mục lục bằng cách quét các dòng được gán nhãn **Heading** (H1, H2, H3...)
        
    -   **Lỗi:** Cả 7 tiêu đề đều mang nhãn **Normal** (chỉ đổi kích thước, in đậm, tô màu thủ công). Word hiểu đó là văn bản thường nên không đưa vào mục lục
       
2.  **Tác hại khi nhầm cấp Heading (2.1.1 Tiểu ban Kỹ thuật):**
    
    -   Lầm từ **H3** sang **H2** sẽ khiến dòng `2.1.1` bị nằm **thẳng hàng ngang** với dòng cha `2.1` thay vì **thụt lùi vào trong**, làm sai lệch cấu trúc phân cấp
    
### PHẦN 2: SỬA LỖI & NGHIỆM THU

#### 3. Các bước gán Heading chuẩn cho 7 tiêu đề

-   **Gán Heading 1 (`Ctrl + Alt + 1`):**
    
    -   `1. Thông tin chung hội nghị`
        
    -   `2. Cơ cấu ban tổ chức`
        
    -   `3. Lịch trình sự kiện`
        
-   **Gán Heading 2 
    
    -   `1.1. Tên hội nghị`
        
    -   `1.2. Thời gian & địa điểm`
        
    -   `2.1. Ban Nội dung`
        
-   **Gán Heading 3 (`Ctrl + Alt + 3`):**
    
    -   `2.1.1. Tiểu ban Kỹ thuật`
        

> **Tạo mục lục:** Đặt chuột ở trang đầu $\rightarrow$ Tab **References** $\rightarrow$ **Table of Contents** $\rightarrow$ Chọn **Automatic Table 1**

#### 4. Bẫy dữ liệu (Mục 3 bị đẩy sang trang 4)

-   **Trả lời:** Mục lục **KHÔNG** tự cập nhật số trang mới nếu bạn không ra lệnh
    
-   **Cách xử lý:**
    
    1.  Click vào bảng mục lục
        
    2.  Bấm phím **`F9`** (hoặc chọn **Update Table...**)
        
    3.  Chọn **Update page numbers only** (chỉ cập nhật số trang) hoặc **Update entire table** $\rightarrow$ Bấm **OK**
