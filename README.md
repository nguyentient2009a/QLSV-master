# PHẦN MỀM QUẢN LÝ SINH VIÊN

  Với sự phát triển nhanh chóng của công nghệ thông tin đã ra đời nhiều công cụ hữu ích giúp chúng ta tiết kiệm rất nhiều thời gian và chi phí. Nhiều phần mềm trong lĩnh vực công  nghệ thông tin nhanh chóng ra đời đã góp phần đáng kể. Chính vì vậy, mỗi công ty, mỗi cơ quan đều muốn xây dựng riêng cho mình một phần mềm quản lý.

  Để xây dựng một phần mềm có năng suất hoạt động tốt, cần có sự phối hợp về kiến thức cũng như ý tưởng của nhiều thành viên gộp lại. Vì vậy cần có một hệ thống quản lý phiên bản phân tán có thể giúp các thành viên dễ dàng trao đổi kiến thức cũng như code xây dựng phần mềm.
  
  Xuất phát từ những nhu cầu đó và theo yêu cầu môn học, nhóm chúng em xây dựng một phần mềm “Quản lý sinh viên” trên nền tảng ngôn ngữ lập trình C#, hệ quản trị cơ sở dữ liệu SQL và được xây dựng theo hướng phần mềm mã nguồn mở với các phiên bản được quản lý trên kho Github – một hệ thống quản lý phiên bản phân tán.
  
  `Mục tiêu` là nhằm tạo ra phần mềm Quản lý sinh viên với các chức năng cơ bản của một phần mềm quản lý, đồng thời nắm bắt được cách tổ chức mã nguồn theo mô hình 3 lớp và trao đổi code cũng như tài liệu xây dựng trên môi trường Github. 
  
  Qua đó tạo điều kiện cho các nhà `phát triển` có thể fix các lỗi và phát triển phần mềm tối ưu hơn, có thể áp dụng vào trong quá trình thực tế. Bởi lẽ do kiến thức còn hạn chế, ý tưởng chưa có nhiều nên phần mềm chưa được hoàn thiện.
## Thành viên nhóm thực hiện

#### Mã nguồn được phân chia theo 3 Tầng như sau: 

* Tầng `QuanLySinhVien_BLL` chứa các module xử lý các sự kiện trong từng Form giao diện, file *xulichuoi.cs* đảm nhiệm việc định dạng dữ liệu vào theo chuẩn


* Tầng `QuanLySinhVien_BLL` chứa các module dữ liệu, file *DB_connect.cs* chứa kết nối đến **CSDL**, file *Data.cs* chứa dữ liệu từ các bảng trong  **CSDL**


* Tầng `QuanLySinhVien_GUI` chứa các Form giao diện, *frmProMain.cs* trong tầng này sẽ là chương trình chính gọi tất cả các Form khác khi click sự kiện.


## Nền tảng xây dựng
#### [C# .NET](https://docs.microsoft.com/en-us/dotnet/csharp/getting-started/introduction-to-the-csharp-language-and-the-net-framework) - Nền tảng hệ thống phần mềm
* C # là một ngôn ngữ lập trình hiện đại được phát triển bởi Microsoft và được phê duyệt bởi European Computer Manufacturers Association (ECMA) và International Standards Organization (ISO).

* C # được phát triển bởi Anders Hejlsberg và nhóm của ông trong việc phát triển .Net Framework.

* C # được thiết kế cho các ngôn ngữ chung cơ sở hạ tầng (Common Language Infrastructure – CLI), trong đó bao gồm các mã (Executable Code) và môi trường thực thi (Runtime Environment) cho phép sử dụng các ngôn ngữ cấp cao khác nhau trên đa nền tảng máy tính và kiến trúc khác nhau.

#### Ngôn ngữ ra đời cùng với .NET

* Kết hợp C++ và Java. Hướng đối tượng. Hướng thành phần. Mạnh mẽ (robust) và bền vững (durable). Mọi thứ trong C# đều Object oriented. Kể cả kiểu dữ liệu cơ bản. Chỉ cho phép đơn kế thừa. Dùng interface để khắc phục. Lớp Object là cha của tất cả các lớp. Mọi lớp đều dẫn xuất từ Object. Cho phép chia chương trình thành các thành phần nhỏ độc lập nhau. Mỗi lớp gói gọn trong một file, không cần file header như C/C++. Bổ sung khái niệm namespace để gom nhóm các lớp. Bổ sung khái niệm “property” cho các lớp. Khái niệm delegate & event

* Vai trò C# trong .NET Framework.NET runtime sẽ phổ biến và được cài trong máy client. Việc cài đặt App C# như là tái phân phối các thành phần .NET Nhiều App thương mại sẽ được cài đặt bằng C#.

* C# tạo cơ hội cho tổ chức xây dựng các App Client/Server n-tier. Kết nối ADO.NET cho phép truy cập nhanh chóng & dễ dàng với SQL Server, Oracle… Cách tổ chức .NET cho phép hạn chế những vấn đề phiên bản.

#### [MS SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2016) - Nền tảng cơ sở dữ liệu
* SQL Server là một hệ quản trị cơ sở dữ liệu quan hệ (Relational Database Management System (RDBMS) ) sử dụng câu lệnh SQL (Transact-SQL) để trao đổi dữ liệu giữa máy Client và máy cài SQL Server. Một RDBMS bao gồm databases, database engine và các ứng dụng dùng để quản lý dữ liệu và các bộ phận khác nhau trong RDBMS.

* SQL Server được tối ưu để có thể chạy trên môi trường cơ sở dữ liệu rất lớn (Very Large Database Environment) lên đến Tera-Byte và có thể phục vụ cùng lúc cho hàng ngàn user. SQL Server có thể kết hợp “ăn ý” với các server khác như Microsoft Internet Information Server (IIS), E-Commerce Server, Proxy Server….

## Danh sách lỗi
- Giao diện chưa đẹp,
- Thiết kế dữ liệu chưa hợp lý.
**_Một lần nữa, chúng em xin chân thành cảm ơn!_**
