📊 Project PBI: Phân Tích Dữ Liệu bằng SQL, Power BI & Tableau
Dự án tổng hợp các bài thực hành phân tích dữ liệu thực tế sử dụng SQL, Power BI và Tableau trong các lĩnh vực: bán lẻ, chăm sóc khách hàng, bất động sản và y tế. Mục tiêu là xây dựng báo cáo phân tích từ dữ liệu thô đến trình bày trực quan hóa.

 

📁 Cấu trúc thư mục

├── DataWarehouseAnalytics.sql             # Phân tích hiệu suất bán hàng từ mô hình Data Warehouse
├── Power BI full project.pbix             # Báo cáo phân tích bán hàng bằng Power BI
├── COVID SQL Project.sql                  # Phân tích dữ liệu COVID-19 bằng SQL
├── Call Center Tableau Dashboard.pptx     # Báo cáo Tableau về hiệu suất trung tâm cuộc gọi
└── SQL Housing Data for Data Cleaning.sql # Làm sạch dữ liệu nhà ở bằng SQL
 

📌 Mục tiêu dự án
Làm quen với kỹ năng phân tích dữ liệu đa lĩnh vực.

Ứng dụng kỹ thuật SQL nâng cao như CTE, Window Function.

Thiết kế báo cáo dashboard tương tác với Power BI và Tableau.

Làm sạch, chuẩn hóa dữ liệu để sẵn sàng cho phân tích.

 

📊 Nội dung từng phần
1. Phân tích bán hàng qua mô hình Data Warehouse
Truy vấn dữ liệu từ các bảng fact và dimension.

Tính tổng doanh thu, doanh thu theo thời gian, sản phẩm, khách hàng.

Sử dụng các hàm cửa sổ như SUM OVER, RANK, LAG để phân tích nâng cao.

Trực quan hóa bằng Power BI (file: Power BI full project.pbix).

▶️ Chạy bằng SSMS hoặc dòng lệnh:


sqlcmd -S .\SQLEXPRESS -i DataWarehouseAnalytics.sql
 

2. Phân tích dữ liệu COVID-19 bằng SQL
Truy xuất và tổng hợp dữ liệu các ca nhiễm, hồi phục và tử vong.

Phân tích theo thời gian và quốc gia.

Sử dụng GROUP BY, JOIN và hàm thời gian trong SQL Server.

 

3. Báo cáo hiệu suất trung tâm cuộc gọi (Call Center)
Trình bày bằng Tableau dưới dạng slide (.pptx).

Gồm các chỉ số như: thời gian chờ trung bình, tỷ lệ giải quyết cuộc gọi, khối lượng cuộc gọi theo giờ/ngày.

 

4. Làm sạch dữ liệu nhà ở (Housing Data Cleaning)
Xử lý dữ liệu trùng, lỗi, định dạng sai.

Chuẩn hóa cột, đổi kiểu dữ liệu.

Loại bỏ dữ liệu thiếu, tạo bảng chuẩn hóa để phục vụ phân tích sau này.

 

🛠 Công cụ sử dụng

✔️ Microsoft SQL Server + SSMS (SQL Server Management Studio)
✔️ Power BI Desktop
✔️ Tableau Public / Desktop
✔️ Excel
✔️ GitHub (quản lý mã nguồn)
 

🚀 Hướng dẫn sử dụng
Clone hoặc tải repo về máy:


git clone https://github.com/CuongDAol/Project-pbi
Mở các file SQL bằng SSMS để truy vấn.

Mở .pbix bằng Power BI Desktop để xem báo cáo.

Xem báo cáo Tableau trong file .pptx trình chiếu.

 

📬 Liên hệ
Tác giả:Bùi Mạnh Cường
📧 Email: buipg0801@gmail.com
📎 GitHub: https://github.com/CuongDAol
