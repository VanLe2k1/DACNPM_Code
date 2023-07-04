# DACNPM
Bài tập lớn môn Đồ án CNPM
Chủ đề: Lập trình website bằng công nghệ Asp.net 
1,Tên Project : DACNPM  
2,Thành viên tham gia: 
	- Lê Văn Văn
	- Nguyễn Việt Phương
3,Tổng quan Project 
	- Project được thực hiện bằng công nghệ Asp.net với mô hình MVC có sử dụng Entity Framework Core.
	- Hệ quản trị csdl : SQLServer 
4,Công cụ hỗ trợ 
	- Visual Studio 2022 
	- SQL Server Management Studio 2019 
5,Cách cài đặt cấu hình khi chạy trên thiết bị khác
	- Cần tạo csdl trên thiết bị đó bằng cách: mở file DACNPM.sql bằng hệ quản trị csdl SQLServer ->Chạy câu truy vấn (Bấm Execute)->CSDL sẽ được tạo. 
	- Mở file DACNPM.sln bằng công cụ Visual Studio, chọn view -> SQL Server Object Explorer => Hộp (SQL Server Object Explorer) xuất hiện.
	- Để kết nối với csdl vừa cài đặt trên SQL Server: chọn Add SQL Server -> Chọn Server (trùng với Server cài đặt csdl ở trên).
	- Khi chọn đúng cấu hình Server thì csdl sẽ xuất hiện ở hộp Database Name ( chỉ cần nhấp vào và chọn csdl vừa cài đặt ) sau đó nhấn Connect 
	- Sau khi kết nối thành công, chọn vào csdl DACNPM qua đường dẫn SQL Server. 
	- Copy thuộc tính Connection string ở bảng Properties. 
	- Vào View chọn Solution Explorer và mở file appsetting.json. 
	- Thay đường dẫn ConnectionString bằng đường dẫn vừa copy ở trên. 
	- Sau khi thực hiện các bước cần build lại và chạy. 


	
