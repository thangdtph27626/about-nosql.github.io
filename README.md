<p align="center">
 <h1 align="center">Tìm hiểu về Nosql</h1>
</p> 

## Cơ sở dữ liệu NoSQL là gì?
Cơ sở dữ liệu NoSQL là Cơ sở dữ liệu được xây dựng dành riêng cho mô hình dữ liệu và có sơ đồ linh hoạt để xây dựng các ứng dụng hiện đại. Cơ sở dữ liệu NoSQL được công nhận rộng rãi vì khả năng dễ phát triển, chức năng cũng như hiệu năng ở quy mô lớn. Trang này có các tài nguyên giúp bạn hiểu thêm về cơ sở dữ liệu NoSQL và bắt đầu sử dụng.

## Cơ sở dữ liệu NoSQL  hoạt động như thế nào?
Cơ sở dữ liệu NoSQL sử dụng nhiều mô hình dữ liệu để truy cập và quản lý dữ liệu. Các loại cơ sở dữ liệu này được tối ưu hóa dành riêng cho các ứng dụng yêu cầu mô hình dữ liệu linh hoạt có lượng dữ liệu lớn và độ trễ thấp, có thể đạt được bằng cách giảm bớt một số hạn chế về tính nhất quán của dữ liệu của các cơ sở dữ liệu khác.

Hãy xem ví dụ về mô hình sơ đồ dành cho cơ sở dữ liệu sách đơn giản:

- Trong cơ sở dữ liệu quan hệ, hồ sơ về một cuốn sách thường được phân tách (hay còn gọi là "chuẩn hóa") và lưu trữ trong các bảng tách biệt nhau, còn mối quan hệ được quy định bằng các ràng buộc khóa ngoại và khóa chính. Trong ví dụ này, bảng Sách có các cột cho ISBN, Tên sách và Số phiên bản, bảng Tác giả có các cột cho ID tác giả và Tên tác giả và cuối cùng, bảng Tác giả–ISBN có các cột cho ID tác giả và ISBN. Mô hình quan hệ được thiết kế để cho phép các cơ sở dữ liệu này thực thi tính toàn vẹn tham chiếu giữa nhiều bảng trong cơ sở dữ liệu, được chuẩn hóa để giảm dư thừa và thường được tối ưu hóa cho mục đích lưu trữ.
- Trong cơ sở dữ liệu NoSQL, hồ sơ về một cuốn sách thường được lưu trữ dưới dạng văn bản JSON. Với từng quyển sách, mục, ISBN, Tên sách, Số phiên bản, Tên tác giả và ID tác giả được lưu trữ dưới dạng thuộc tính trong một văn bản duy nhất. Trong mô hình này, dữ liệu được tối ưu hóa cho việc phát triển trực quan và khả năng thay đổi quy mô theo chiều ngang.

## Ưu nhược của NoSQL
Một số ưu điểm và nhược điểm cần biết về nosql.

### 1. Ưu điểm

 Có một số lợi thế, điểm mạnh khi làm việc với cơ sở dữ liệu NoSQL như MongoDB và Cassandra. Những ưu điểm chính của nosql là khả năng mở rộng và tính sẵn sàng cao.

- NoSQL giải quyết được các vấn đề dữ liệu lớn(big data) về các hệ thống thông tin hoặc là phân tán dữ liệu.
- Việc mở rộng phạm vi là mềm dẻo: NoSQL thay thế câu thần chú cũ của các nhà quản trị CSDL về việc ‘mở rộng phạm vi’ với một thứ mới: ‘mở rộng ra ngoài’. Thay vì phải bổ sung thêm những máy chủ lớn hơn để tải nhiều dữ liệu hơn, thì CSDL NoSQL cho phép một công ty phân tán tải qua nhiều máy chủ khi tải gia tăng.
- High availability: Khả năng tự động sao chép trong MongoDB làm cho nó rất tốt trong mọi trường hợp vì trong trường hợp có bất kỳ lỗi nào, dữ liệu sẽ tự động sao chép về trạng thái nhất quán trước đó.

### 2. Nhược điểm
Bên cạnh những ưu điểm của nó thì NoSQL Database cũng có những nhược điểm sau:
- Quản lý dữ liệu: Mục đích của các công cụ dữ liệu lớn là làm cho việc quản lý một lượng lớn dữ liệu trở nên đơn giản nhất. Nhưng quản lý dữ liệu trong NoSQL phức tạp hơn nhiều so với cơ sở dữ liệu quan hệ. Đặc biệt, NoSQL nổi tiếng là khó cài đặt và thậm chí là để quản lý nó hằng ngày cũng tốn khá nhiều thời gian.
- Sao lưu dữ liệu: Sao lưu là một điểm yếu lớn đối với một số cơ sở dữ liệu NoSQL như MongoDB. Nó không có cách tiếp cận để làm sao lưu dữ liệu một cách nhất quán.
- Thiếu tính nhất quán: NoSQL đánh đổi sự nhất quán để ưu tiên tốc độ, hiệu suất hiệu quả hơn.
- Trọng tâm hẹp: Cơ sở dữ liệu NoSQL có trọng tâm rất hẹp vì nó chủ yếu được thiết kế để lưu trữ nhưng nó cung cấp rất ít chức năng.
- Mã nguồn mở: NoSQL là cơ sở dữ liệu mã nguồn mở và không có tiêu chuẩn đáng tin cậy cho NoSQL được nêu ra.
- Không có lược đồ: Ngay cả khi bạn lấy dữ liệu ở dạng tự do, bạn hầu như luôn cần áp đặt các ràng buộc để làm cho nó hữu ích. Với NoSQL, trách nhiệm sẽ được chuyển từ cơ sở dữ liệu sang nhà phát triển, lập trình ứng dụng.
- Kỹ năng NoSQL: Một hạn chế khác đối với NoSQL là người sử dụng có thể sẽ thiếu các kỹ năng chuyên môn ở mức tương đối vì hệ thống này còn khá mới và không phải ai cũng biết sử dụng nó một cách thành thạo.

## Khi nào bạn nên sử dụng NoSQL?
Bạn nên áp dụng NoSQL Database trong những trường hợp sau:

- SQL là ngôn ngữ đơn giản nhất được sử dụng để giao tiếp với RDBMS
- Phân tích các phiên liên quan đến hành vi và tùy chỉnh
- Tạo trang tổng quan tùy chỉnh
- Nó cho phép bạn lưu trữ và lấy dữ liệu từ cơ sở dữ liệu một cách nhanh chóng
- Được ưu tiên khi bạn muốn sử dụng các phép nối và thực hiện các truy vấn phức tạp

## Các hệ thống NoSQL phổ biến hiện nay
Với CSDL NoSQL, dữ liệu có thể được lưu trữ theo kiểu đơn giản lược đồ hoặc dạng tự do. Các hệ thống nosql phổ biến hiện nay là:

- Graph database(ví dụ: Neo4j- là một trong những Graph Database phổ biển nhất hiện nay.): Mô tả và lưu trữ dữ liệu dưới dạng đồ thị các đối tượng và mối quan hệ của các đối tượng, một cách trực quan và dễ dàng truy vấn. Với mỗi node trong biểu đồ là một đoạn dữ liệu dạng tự do.
- Document database: (ví dụ: CouchDB, MongoDB): Dữ liệu khi được thêm vào sẽ được lưu trữ dưới dạng cấu trúc JSON tự do hoặc là “tài liệu”.
- Key-value stores(ví dụ: Redis, Riak): Lưu trữ kiểu key-value là kiểu lưu trữ dữ liệu NoSQL đơn giản nhất sử dụng từ một API. Chúng ta có thể nhận giá trị cho khóa, thực hiện đặt một giá trị cho một khóa, hoặc xóa một khóa từ dữ liệu. Các giá trị dạng tự do – từ các số nguyên hoặc chuỗi đơn giản đến các tài liệu JSON phức tạp.
- Wide column stores(ví dụ: HBase, Cassandra): Dữ liệu hệ thống sẽ được lưu trữ dạng cột thay vì theo hàng như trong các hệ thống SQL thông thường. Ở bất kỳ số cột có thể được nhóm hoặc tổng hợp khi cần thiết cho các truy vấn hoặc ở chế độ xem dữ liệu.

## Phân biệt sql và nosql

<table>
<thead>
<tr>
<th>Tham số</th>
<th>SQL</th>
<th>NoSQL</th>
</tr>
</thead>
<tbody>
<tr>
<td>Định nghĩa</td>
<td>Cơ sở dữ liệu SQL chủ yếu được gọi là RDBMS hoặc Cơ sở dữ liệu quan hệ</td>
<td>Cơ sở dữ liệu NoSQL chủ yếu được gọi là cơ sở dữ liệu không liên quan hoặc phân tán</td>
</tr>
<tr>
<td>Design for</td>
<td>RDBMS truyền thống sử dụng cú pháp và truy vấn SQL để phân tích và lấy dữ liệu để có thêm thông tin chi tiết. Chúng được sử dụng cho các hệ thống OLAP.</td>
<td>Hệ thống cơ sở dữ liệu NoSQL bao gồm nhiều loại công nghệ cơ sở dữ liệu khác nhau. Các cơ sở dữ liệu này được phát triển để đáp ứng nhu cầu trình bày cho sự phát triển của ứng dụng hiện đại.</td>
</tr>
<tr>
<td>Ngôn ngữ Query</td>
<td>Structured query language (SQL)</td>
<td>Không có ngôn ngữ query</td>
</tr>
<tr>
<td>Type</td>
<td>SQL databases là cơ sở dữ liệu dựa trên bảng</td>
<td>NoSQL databases có thể dựa trên tài liệu, cặp khóa-giá trị, cơ sở dữ liệu biểu đồ</td>
</tr>
<tr>
<td>Schema</td>
<td>SQL databases có lược đồ được xác định trước</td>
<td>NoSQL databases sử dụng lược đồ động cho dữ liệu phi cấu trúc.</td>
</tr>
<tr>
<td>Khả năng mở rộng</td>
<td>SQL databases có thể mở rộng theo chiều dọc</td>
<td>NoSQL databases có thể mở rộng theo chiều ngang</td>
</tr>
<tr>
<td>Ví dụ</td>
<td>Oracle, Postgres, and MS-SQL.</td>
<td>MongoDB, Redis, , Neo4j, Cassandra, Hbase.</td>
</tr>
<tr>
<td>Phù hợp cho</td>
<td>Đây là 1 lựa chọn lý tưởng cho môi trường truy vấn phức tạp</td>
<td>Không phù hợp với truy vấn phức tạp</td>
</tr>
<tr>
<td>Lưu trữ dữ liệu phân cấp</td>
<td>SQL databases không thích hợp cho việc lưu trữ dữ liệu phân cấp.</td>
<td>Phù hợp hơn cho kho lưu trữ dữ liệu phân cấp vì nó hỗ trợ phương thức cặp khóa-giá trị.</td>
</tr>
<tr>
<td>Variations</td>
<td>Một loại có biến thể nhỏ</td>
<td>Nhiều loại khác nhau bao gồm các kho khóa-giá trị, cơ sở dữ liệu tài liệu và cơ sở dữ liệu đồ thị.</td>
</tr>
<tr>
<td>Năm phát triển</td>
<td>Nó được phát triển vào những năm 1970 để giải quyết các vấn đề với lưu trữ tệp phẳng</td>
<td>Được phát triển vào cuối những năm 2000 để khắc phục các vấn đề và hạn chế của SQL databases.</td>
</tr>
<tr>
<td>Open-source</td>
<td>Một sự kết hợp của mã nguồn mở như Postgres &amp; MySQL, và thương mại như Oracle Database.</td>
<td>Open-source</td>
</tr>
<tr>
<td>Tính nhất quán</td>
<td>Nó phải được cấu hình cho sự nhất quán chặt chẽ.</td>
<td>Nó phụ thuộc vào DBMS như một số cung cấp tính nhất quán mạnh mẽ như MongoDB, trong khi những người khác cung cấp chỉ cung cấp sự nhất quán cuối cùng, như Cassandra.</td>
</tr>
<tr>
<td>Được sử dụng tốt nhất cho</td>
<td>RDBMS database là tùy chọn thích hợp để giải quyết các vấn đề về ACID.</td>
<td>NoSQL được sử dụng tốt nhất để giải quyết các vấn đề về tính khả dụng của dữ liệu</td>
</tr>
<tr>
<td>Tầm quan trọng</td>
<td>Nó nên được sử dụng khi hiệu lực dữ liệu là siêu quan trọng</td>
<td>Sử dụng khi nó quan trọng hơn để có dữ liệu nhanh hơn dữ liệu chính xác</td>
</tr>
<tr>
<td>Lựa chọn tốt nhất</td>
<td>Khi bạn cần hỗ trợ truy vấn động</td>
<td>Sử dụng khi bạn cần mở rộng quy mô dựa trên yêu cầu thay đổi</td>
</tr>
<tr>
<td>Hardware</td>
<td>Specialized DB hardware (Oracle Exadata, etc.)</td>
<td>Commodity hardware</td>
</tr>
<tr>
<td>Network</td>
<td>Highly available network (Infiniband, Fabric Path, etc.)</td>
<td>Commodity network (Ethernet, etc.)</td>
</tr>
<tr>
<td>Loại lưu trữ</td>
<td>Highly Available Storage (SAN, RAID, etc.)</td>
<td>Commodity drives storage (standard HDDs, JBOD)</td>
</tr>
<tr>
<td>Tính năng tốt nhất</td>
<td>Hỗ trợ đa nền tảng, Bảo mật và miễn phí</td>
<td>Dễ sử dụng, hiệu suất cao và công cụ linh hoạt.</td>
</tr>
<tr>
<td>Mô hình  ACID và BASE</td>
<td>ACID (Atomicity, nhất quán, cách ly và độ bền) là một chuẩn cho RDBMS</td>
<td>Cơ bản (Về cơ bản có sẵn, trạng thái mềm, phù hợp cuối cùng) là một mô hình của nhiều hệ thống NoSQL</td>
</tr>
<tr>
<td>Performance</td>
<td>SQL hoạt động tốt và nhanh thì việc desgin tốt là cực kì quan trọng và ngược lại.</td>
<td>Nhanh hơn SQL NoSQL thì denormalized cho phép bạn lấy được tất cả thông tin về một item cụ thể với các codition mà không cần JOIN liên quan hoặc truy vấn SQL phức tạp.</td>
</tr>
<tr>
<td>Kết luận</td>
<td>Dự án đã có yêu cầu dữ liệu rõ ràng xác định quan hệ logic có thể được xác định trước.</td>
<td>Phù hợp với những dự án yêu cầu dữ liệu không liên quan, khó xác định, đơn giản mềm dẻo khi đang phát triển</td>
</tr>
</tbody>
</table>
