# CLEAN CODE


### 1. Đặt tên:

**đặt tên biến:**

-Việc sử dụng một tên biến tiết lộ ý định sẽ dễ dàng cho việc đọc và hiểu code, từ đó việc thay đổi code cũng sẽ dễ dàng hơn

-Một biến cần comment để giúp thể hiện ý nghĩa không phải là một cách đặt tên biến tốt.

![đặt tên biến xấu](images/code1.png)

-Nên sử dụng các danh từ đặt tên cho các biến.

-Các giá trị Searchable nên đặt thành một hằng số nhằm đảm bảo việc quản trị thay đổi sau này dễ dàng hơn.

![đặt tên biến seachable đẹp](images/cleancode2.png)

-Tránh việc mã hóa ghi tắt làm người đọc rối.

-Ví dụ cho việc đặt tên biến đẹp:


![đặt tên biến đẹp](images/cleancode3.png)

**Đặt tên class và Object**

-Tên class và object phải là danh từ hoặc cụm danh từ (Vd: Customer, Animal)

-Tên class không nên là động từ

**Đặt tên cho method**

-Tên method nên là động từ hoặc cụm động từ (Vd: postPayment, saveUserInfomation,..)

-Khi constructors được overloads nhiều lần nên sử dụng factory với tên biểu diễn cho argument.

![đặt tên method đẹp](images/cleancode4.png)

![factory](images/factory.png)

-Dùng những từ đơn giản mọi người đều hiểu để đặt cho method, "Don't Be Cute"

-Tránh sử dụng những từ có 2 nghĩa, hoặc sử dụng 2 từ cùng một nghĩa, điều này làm cho việc code dễ hiểu và đỡ rắc rối hơn.

### 2. Functions

**Nhỏ**

-Luật đầu tiên là hàm phải nhỏ, luật thứ  2 là hàm phải nhỏ hơn nữa. Một hàm tốt chỉ bao gồm từ 20-30 dòng code. Hàm càng dài khả năng sinh ra lỗi sẽ càng cao.

**Chỉ làm một việc**

-Giúp tái sử dụng các hàm một cách tiện lợi, không những thế việc kiểm tra lỗi sẽ nhanh hơn.

**Tham số cho hàm**

-Không nên có quá 3 tham số đầu vào cho một hàm, việc hiểu một hàm với 1 tham số sẽ dễ dàng hơn nhiều so với việc một hàm có 2 tham số. 

-Việc đối tượng hóa tham số không phải là một cách gian lận để giảm tham số mà còn giúp cho code dễ hiểu hơn.








