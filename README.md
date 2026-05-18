👟 Adidas US Sales Performance Analysis

📌 Project Overview

Dự án này thực hiện phân tích chuyên sâu bộ dữ liệu bán hàng của Adidas tại thị trường Hoa Kỳ (giai đoạn 2020 - 2021). Mục tiêu chính là đánh giá hiệu quả kinh doanh đa chiều, từ đó đề xuất các chiến lược tối ưu hóa kênh phân phối, quản lý danh mục sản phẩm và phân bổ nguồn lực theo khu vực địa lý.

📊 Dataset

Nguồn: Adidas US Sales Dataset (Kaggle).

Quy mô: 9,648 giao dịch bán hàng.

Các thuộc tính chính: Retailer, Invoice Date, Region, State, City, Product, Price per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin, Sales Method.

🛠 Methodology (Quy trình thực hiện)

Data Cleaning & Preprocessing:

Chuyển đổi định dạng dữ liệu (Datetime, Numeric).

Xử lý Outliers (giá trị ngoại lai) bằng phương pháp Capping (99th percentile) để loại bỏ nhiễu từ các đơn hàng sỉ (B2B) mà vẫn giữ được xu hướng thị trường bán lẻ.

Kiểm tra tính nhất quán giữa Doanh thu, Giá bán và Sản lượng.

Exploratory Data Analysis (EDA):

Thời gian: Phân tích xu hướng biến động theo tháng/quý để xác định tính mùa vụ.

Địa lý: So sánh hiệu suất giữa các vùng (West, Northeast, Southeast...) và các bang trọng điểm.

Sản phẩm: Phân tích ma trận Sản lượng - Biên lợi nhuận để phân loại nhóm sản phẩm "Ngôi sao".

Kênh phân phối: Đánh giá hiệu quả của các kênh Online, Outlet và In-store.

📈 Key Findings (Khám phá quan trọng)

Sự bứt phá sau đại dịch: Doanh thu năm 2021 tăng trưởng gấp 4 lần so với năm 2020 nhờ hiện tượng "Revenge Spending" và sự phục hồi của các sự kiện thể thao lớn (Euro 2020, Olympic Tokyo).

Hiệu quả kênh Online: Kênh Online có biên lợi nhuận cao nhất (~45%), khẳng định chiến lược Direct-to-Consumer (DTC) đang đi đúng hướng.

Khu vực dẫn dắt: Vùng West (Phía Tây) là "đầu tàu" doanh thu, chiếm hơn 30% thị phần toàn quốc.


💡 Business Recommendations

Tái cấu trúc danh mục: Tập trung nguồn lực Marketing vào dòng sản phẩm "Ngôi sao" và tối ưu hóa chi phí cho các dòng sản phẩm biên lãi thấp như Athletic Footwear.

Chiến lược vùng miền: Tăng cường trải nghiệm khách hàng tại khu vực Southeast (nơi khách hàng ưu tiên In-store) và đẩy mạnh Marketing số tại khu vực West & Northeast.

Tối ưu kênh Online: Khai thác tiềm năng AOV (Giá trị đơn hàng trung bình) cao trên Amazon và website chính thức thông qua các bộ sưu tập giới hạn.

💻 Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn.

Analysis Techniques: Descriptive Statistics, Trend Analysis, Pareto Analysis (80/20).
