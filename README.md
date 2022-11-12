# tasc_training_day1

Class: Bao gồm 2 thành phần thuộc tính (attribute) và phương thức (method).

Object: Là thể hiện của class, bao gồm các thuộc tính của class.

Constructor: Phương thức khởi tạo của class, sử dụng để khai báo các thuộc tính của class, luôn có 1 constructor rỗng khi class đc tạo ra.

Tham chiếu: Lưu trữ vào 1 đại chỉ tham khảo, khi sử dụng sẽ thông qua địa chỉ này để lưu, lấy dữ liệu của biến.

Tham trị: Khi khai báo kiểu dữ liệu nguyên thủy cho các biến, giá trị đó sẽ được lưu tại địa chỉ bộ nhớ dành cho biến đó, 2 biến có tên khác nhau có địa chỉ ô nhớ khác nhau. Khi được sử dụng, sẽ tạo lấy trực tiếp giá trị của biến chứ không làm việc với vùng bộ nhớ lưu trữ giá trị.

Equals và == : Equals so sánh giá trong khi == so sánh địa chỉ ô nhớ.

Interface: Trong interface sẽ định nghĩa các phương thức muốn sử dụng, class implements interface đó sẽ override các phương thức đó với tham số đầu vào định nghĩa sẵn.

Abstract class: Là 1 lớp trừu tượng, trong đó chứa các phương thức trừu tượng. Các class khi kế thừa abstract class sẽ ogaru định nghĩa lại các phương thức trừu tượng đc khai báo trong abstract class.

Final: Từ khóa final đc sử dụng khi khai báo biến, phương thức hoặc lớp.

    - Biến final: Khi đc khai báo final, biến sẽ trở thành hằng số.
    - Phương thức final: Không thể bị ghi đè (override).
    - Lớp final: Không thể bị kế thừa bởi lớp khác.

Static: Từ khóa static đc sử dụng khi khai báo biến, phương thức hoặc khối static.

    - Biến static: Biến static (biến tĩnh) chỉ cấp phát địa chỉ bộ nhớ 1 lần khi tải lớp chứa nó. Có thể sử dụng để khai báo thông tin chung cho các thuộc tính trong lớp đó.
    - Phương thức static:   + Thuộc lớp chứ k phải đối tượng của lớp.
                            + Phương thức static có thể đc gọi mà k cần tạo instance của lớp.
                            + Có thể gọi biến static và thay đổi giá trị của nó.
    - Khối static: Sử dụng để khai báo các thành viên static. Được chạy trước khi chạy hàm main.
    
