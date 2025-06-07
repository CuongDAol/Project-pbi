# 📊 Project PBI: Phân Tích Dữ Liệu bằng SQL, Power BI & Tableau

Dự án tổng hợp các bài thực hành phân tích dữ liệu thực tế sử dụng SQL, Power BI và Tableau trong các lĩnh vực: bán lẻ, chăm sóc khách hàng, bất động sản và y tế.
Mục tiêu: Xây dựng báo cáo phân tích từ dữ liệu thô đến trình bày trực quan hóa.

---

## 📁 Cấu trúc thư mục

```bash
├── DataWarehouseAnalytics.sql             # Phân tích hiệu suất bán hàng từ Data Warehouse
├── Power BI full project.pbix             # Báo cáo Power BI
├── COVID SQL Project.sql                  # Phân tích dữ liệu COVID-19
├── Call Center Tableau Dashboard.pptx     # Dashboard Tableau trung tâm cuộc gọi
└── SQL Housing Data for Data Cleaning.sql # Tiền xử lý dữ liệu nhà ở
```

---

## 🌟 Mục tiêu dự án

* ✅ Thực hành phân tích dữ liệu thực tế đa ngành
* ✅ Áp dụng SQL nâng cao: CTE, Window Function
* ✅ Trực quan hóa báo cáo với Power BI và Tableau
* ✅ Chuẩn hóa dữ liệu, làm sạch trước khi phân tích

---

## 🧰 Nội dung chi tiết

### 1. 💳 Phân tích bán hàng từ Data Warehouse

* Truy vấn dữ liệu từ các bảng fact và dimension
* Tính doanh thu theo thời gian, sản phẩm, khách hàng
* Dùng SUM OVER, RANK, LAG để phân tích xu hướng
* Dashboard Power BI: `Power BI full project.pbix`

🔧 Chạy bằng SSMS hoặc CMD:

```bash
sqlcmd -S .\SQLEXPRESS -i DataWarehouseAnalytics.sql
```

---

### 2. 🪜 Phân tích COVID-19 bằng SQL

* Truy vấn số ca nhiễm, hồi phục, tử vong
* Phân tích theo thời gian và quốc gia
* Sử dụng GROUP BY, JOIN, các hàm thời gian trong SQL Server

---

### 3. 📢 Hiệu suất trung tâm cuộc gọi (Call Center)

* Trình bày dạng slide Tableau: `Call Center Tableau Dashboard.pptx`
* Gồm các KPI:

  * ⌚️ Thời gian chờ trung bình
  * ✅ Tỷ lệ giải quyết cuộc gọi
  * 📆 Khối lượng cuộc gọi theo ngày

---

### 4. 🏠 Xử lý dữ liệu nhà ở (Housing Data Cleaning)

* Loại trùng, chuẩn hóa dữ liệu, đổi kiểu cột
* Tạo bảng dữ liệu sạch sẵn sàng cho dashboard hoặc ML

---

## 🛠️ Công cụ sử dụng

```bash
🔢 SQL Server + SSMS
🔍 Power BI Desktop
🔎 Tableau Public/Desktop
📇 Excel
🔸 GitHub
```

---

## 🚀 Bắt đầu sử dụng

1. Tải về report:

```bash
git clone https://github.com/CuongDAol/Project-pbi
```

2. Mở file SQL bằng SSMS để truy vấn
3. Mở file .pbix trong Power BI Desktop để xem dashboard
4. Trình chiếu slide Tableau trong file .pptx

---

## 📅 Tác giả

* Tên GitHub: [CuongDAol](https://github.com/CuongDAol)
* 📧 Email: [cuong.dao.dev@gmail.com](mailto:cuong.dao.dev@gmail.com) (giả định)

---

✨ Cảm ơn bạn đã ghé thăm dự án! Hãy nhấn ⭐ star repo nếu bạn thấy hữu ích!
