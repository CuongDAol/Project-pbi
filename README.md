📊 Data Analytics Projects (SQL & Power BI)
📁 Dự án 1: Data Warehouse Sales Performance Analysis (DataWarehouseAnalytics.sql)
Mô tả
Phân tích hiệu suất bán hàng thông qua mô hình dữ liệu Data Warehouse gồm các bảng: fact_sales, dim_products, dim_customers.

Nội dung chính
Phân tích doanh số theo năm và tháng (YEAR(order_date), DATETRUNC(month, order_date))

Tính toán tổng, trung bình, lũy kế và trung bình trượt doanh số bằng Window Functions

So sánh doanh số sản phẩm theo năm và so với trung bình chung (AVG + LAG)

Phân tích danh mục sản phẩm và phân khúc theo chi phí

Phân khúc khách hàng thành 3 nhóm: VIP, Regular, New dựa trên hành vi chi tiêu và thời gian sử dụng

Tạo VIEW tổng hợp báo cáo khách hàng: đơn hàng, giá trị trung bình, độ mới, v.v.

Kỹ thuật
Window functions: SUM() OVER, AVG() OVER, LAG()

CTE (WITH)

VIEW (CREATE VIEW)

📁 Dự án 2: Data Cleaning - Housing Dataset (SQL Housing Data for Data Cleaning.sql)
Mô tả
Dự án làm sạch dữ liệu bất động sản từ bảng NashvilleHousing với mục tiêu chuẩn hóa, bổ sung, và tổ chức lại dữ liệu.

Nội dung chính
Chuẩn hóa định dạng ngày bán (SaleDate)

Điền dữ liệu thiếu trong PropertyAddress dựa vào ParcelID

Tách địa chỉ và tên chủ nhà thành các cột riêng biệt (Address, City, State)

Chuyển giá trị Yes/No thay cho Y/N trong trường SoldAsVacant

Xoá dòng dữ liệu trùng lặp

Xoá cột không sử dụng (SaleDate)

Kỹ thuật
ISNULL, SUBSTRING, CHARINDEX, PARSENAME, ROW_NUMBER() OVER (...)

ALTER TABLE, UPDATE, DELETE, DROP COLUMN

📁 Dự án 3: COVID-19 Data Analysis (COVID SQL Project.sql)
Mô tả
Phân tích dữ liệu COVID-19 toàn cầu từ bảng Covidfulldata, tập trung vào các chỉ số quan trọng như ca nhiễm, tử vong, và tiêm vaccine.

Nội dung chính
Tạo trường mới cho ngày chuẩn hóa (DateConverted)

Tỷ lệ tử vong tại Hoa Kỳ theo ngày

So sánh số ca nhiễm so với dân số - Tỷ lệ phơi nhiễm

Các quốc gia có tỷ lệ tử vong và ca nhiễm cao nhất

Phân tích theo châu lục

Tổng số liệu toàn cầu về ca nhiễm, tử vong

Tính phần trăm dân số được tiêm vaccine (cộng dồn theo ngày)

Tạo bảng tạm và VIEW để phục vụ dashboard sau này

Kỹ thuật
CTE, TEMP TABLE, VIEW, SUM() OVER (PARTITION BY ...)

CONVERT, ROUND, CONCAT

📊 Dự án 4: Power BI Dashboard (Power BI full project.pbix)
Mô tả
File .pbix đi kèm là dashboard trực quan hoá dữ liệu từ các dự án trên (có thể từ dữ liệu COVID hoặc Data Warehouse).

Gợi ý
Dùng Power BI để hiển thị:

Tổng quan hiệu suất bán hàng theo tháng/năm

Phân tích danh mục và sản phẩm nổi bật

Dashboard khách hàng: AOV, tần suất, phân khúc

Tỷ lệ tử vong & tiêm vaccine theo quốc gia/châu lục

⚙️ Công cụ sử dụng
SQL Server (T-SQL): Xử lý dữ liệu, phân tích, tạo bảng/tầm nhìn/CTE

Power BI: Trực quan hóa dữ liệu

Data Cleaning & Transformation: thông qua query SQL thuần

🏁 Hướng dẫn sử dụng
Import file .sql vào công cụ như SSMS hoặc Azure Data Studio để chạy lần lượt từng block code.

Mở file .pbix trong Power BI Desktop để chỉnh sửa hoặc xem dashboard.

Tùy chỉnh truy vấn hoặc dashboard theo dữ liệu thực tế của bạn.
