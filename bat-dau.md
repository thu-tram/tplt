# Hướng dẫn nhập môn

### Trước khi bắt đầu

Nếu bạn muốn tham gia vào thế giới lập trình, bạn cần nắm vững những kiến thức cơ bản về lập trình.

Có một sự khác biệt lớn giữa *học lập trình* và *học một vài ngôn ngữ lập trình*. Bạn có thể "học" hai ngôn ngữ lập trình, nhưng vẫn chưa thực sự *biết lập trình*. Học một ngôn ngữ lập trình cũng giống như học một ngoại ngữ. Học lập trình giống như học cách tư duy. **Khả năng tư duy không bị giới hạn hay quyết định bởi bất kỳ ngôn ngữ nào**. Nếu bạn học một ngôn ngữ mới, khả năng tư duy của bạn không thay đổi. Lập trình cũng tương tự. Các khái niệm lập trình không phụ thuộc vào ngôn ngữ lập trình cụ thể.

Bài viết này sẽ tập trung vào các khái niệm lập trình, giúp bạn học được bất kỳ ngôn ngữ lập trình nào. Học theo cách này (có lẽ sẽ) nhanh hơn nhiều và bạn cũng không bị phân tâm bởi cú pháp của từng ngôn ngữ.

Mọi người cũng có thể học thêm bài [Week 0 - Scartch](https://www.youtube.com/watch?v=U4sz394szSc&list=PLjj8gpaW-Tn8QOw7HPrDsl-gQjEGFlkil&index=1) để bắt đầu.

<iframe width="560" height="315" src="https://www.youtube.com/embed/U4sz394szSc?si=9MyGvf_POLdHIVXR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Tư duy như một lập trình viên

Chúng ta có thể sử dụng **phương pháp tiếp cận thuật toán** để giải quyết vấn đề.

[Lập trình máy tính (Computer programming)](https://vi.wikipedia.org/wiki/L%E1%BA%ADp_tr%C3%ACnh_m%C3%A1y_t%C3%ADnh) là quá trình thiết kế và xây dựng một chương trình máy tính có thể chạy được. Một chương trình máy tính là **tập hợp các chỉ dẫn** mà máy tính có thể thực thi để hoàn thành một nhiệm vụ cụ thể.

Nói một cách đơn giản, lập trình là việc chỉ cho máy tính những việc cần làm. Để mô tả cho máy tính biết nó cần làm gì, các lập trình viên sử dụng nhiều ngôn ngữ lập trình khác nhau. Bây giờ, hãy lấy giấy bút hoặc mở một trình soạn thảo văn bản bất kỳ và viết ra tất cả các bước bạn cần thực hiện để nấu một bát mì gói thơm ngon, giá rẻ cho chú đỗ nghèo khỉ này. Ví dụ:

* Đến tủ bếp và mở cửa tủ.
* Lấy một gói mì (ở đây tôi lấy mì Hảo Hảo).
* Đóng cửa tủ bếp.
* Mở tủ đựng dụng cụ bếp.
* Lấy thìa, đũa, chảo, nồi.
* Đóng tủ đựng dụng cụ bếp.
* Mở tủ lạnh.
* Lấy các nguyên liệu khác: xúc xích, trứng, giò.
* Đóng tủ lạnh.
* Thái xúc xích, giò.
* Rán trứng.
* Rán xúc xích và giò.
* Đun nước.
* Cho mì vào nồi nấu sơ qua.
* Cho các nguyên liệu đã chế biến vào nồi mì.

Như vậy là xong (à thì nó cũng là một bữa ăn khá *giàu có*). Đây là cách các lập trình viên tư duy. Bạn có thể thấy nó không phức tạp và ai cũng có thể làm được. Dù tui viết cái thuật toán đọc khá là phức tạp, đa phần "thuật toán" nấu mì của mọi người sẽ là:

- Bóc mì
- Cho vắt mì và gia vị vào bát
- Đổ nước sôi
- Đậy nắp
- Chờ 3 phút

Nhưng bạn có thể hình dung cơ bản về cái thứ gọi là "thuật toán" trong lập trình. Bạn biết mình phải làm gì, bạn viết code cho việc đó, sau đó bạn kiểm tra xem nó có hoạt động như mình muốn không. Nếu không, bạn biết mình đã làm sai điều gì đó. Bạn thay đổi code và thử lại cho đến khi tìm được giải pháp đúng.

### Thuật toán

Thuật toán là một tập hợp các quy trình từng bước được xác định rõ ràng, đưa ra câu trả lời đúng cho một vấn đề cụ thể. Một thuật toán hợp lệ cần đáp ứng các điều kiện sau:

* Với cùng input, luôn tạo ra cùng một output.
* Phải rõ ràng, được định nghĩa rành mạch và chỉ có một cách diễn giải duy nhất.
* Phải hữu hạn, nghĩa là cần được thực hiện trong một khoảng thời gian hữu hạn và sử dụng không gian hữu hạn.

Ví dụ điển hình nhất về thuật toán mà bạn đã thấy trong cuộc sống là công thức nấu ăn. Bạn biết cần bao lâu để nấu món ăn đó, cần những nguyên liệu nào và cần chuẩn bị chúng theo thứ tự nào. Nếu bạn làm theo công thức đó hai lần và nấu món ăn theo cùng một cách chính xác, cả hai lần bạn sẽ có được cùng một món ăn như vậy.

Để giải quyết các nhiệm vụ bằng lập trình, điều đầu tiên chúng ta cần làm là thiết kế một thuật toán. Có hai cách để viết thuật toán: sử dụng flowchart (flowchart) hoặc (và) mã giả (pseudocode).

### flowchart (Flowchart)

[flowchart](https://vi.wikipedia.org/wiki/L%C6%B0u_%C4%91%E1%BB%93) (Flowchart) là một loại sơ đồ biểu diễn quy trình làm việc hoặc quy trình. Flowchart cũng có thể được định nghĩa là cách biểu diễn một thuật toán bằng sơ đồ. Là một cách tiếp cận từng bước để giải quyết một nhiệm vụ.

Mỗi flowchart bao gồm các khối xây dựng (building block). Để hiểu flowchart, trước tiên bạn cần biết ý nghĩa của từng building block một. Sau đây là danh sách các building blocks:

![](https://upload.wikimedia.org/wikipedia/commons/c/ce/Flowchart_symbols.png) 

Hiện tại, bạn chỉ cần sử dụng một số lượng nhỏ các building block trong danh sách này. Đây là một Flowchart mẫu:

![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/LampFlowchart.svg/220px-LampFlowchart.svg.png)

### Tuần tự (Sequence)

Các chỉ dẫn trong chương trình được thực thi theo thứ tự chúng được viết. Hãy tạo flowchart cho một nhiệm vụ đơn giản, trong đó người dùng sẽ nhập hai số và chương trình sẽ in ra tổng của hai số đó (Cái này là bài tập). Nhìn vào flowchart ở hình trên, bạn có thấy chương trình được thực hiện từ trên xuống dưới một cách tuần tự không?

### Phân nhánh (Branching)

Nếu một phần code nào đó trong thuật toán chỉ được chạy khi một số điều kiện được đáp ứng, chúng ta cần sử dụng branching (branching). Với branching, chúng ta có thể chia code thành hai hoặc nhiều path (đường dẫn). Để minh họa ví dụ về branching, hãy tạo flowchart cho một chương trình nhận input của người dùng là một số và in ra "Số là số dương" hoặc "Số là số âm".

Nhìn vào flowchart ở hình trên, bạn có thấy một hộp hình thoi có hai nhánh "Yes" và "No" không? Đó chính là Branching

### Vòng lặp (Loop)

Đôi khi trong code, chúng ta cần thực hiện cùng một việc nhiều lần. Chúng ta luôn có hai lựa chọn:

- Một là viết cùng một code nhiều lần
- Hai là sử dụng vòng lặp.

Vấn đề với việc viết cùng một code nhiều lần là nó không gọn gàng và tốn thời gian. Đó là lý do tại sao chúng ta nên sử dụng vòng lặp. Trong lập trình máy tính, vòng lặp là một chuỗi các lệnh được lặp lại liên tục cho đến khi đạt được một điều kiện nhất định. Vòng lặp sẽ lặp lại ba bước: kiểm tra xem biến A có nhỏ hơn biến Counter không, in giá trị của biến Counter và tăng giá trị của biến Counter thêm một (Nhìn thử chương trình dưới đây với `i = Counter` xem).

![](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/For_loop_example.svg/170px-For_loop_example.svg.png)

### Biến số (Variable)

Variable là các vị trí trong bộ nhớ có tên và là nơi chúng ta lưu trữ dữ liệu từ input. Giá trị của mỗi biến có thể thay đổi trong quá trình thực thi chương trình. Để truy cập giá trị của một biến, chúng ta chỉ cần viết tên của biến đó. Mỗi biến có tên, giá trị và kiểu. Tôi sẽ nói về kiểu dữ liệu sau. Để gán giá trị cho một biến, chúng ta cần viết tên biến, sau đó là dấu bằng '=' và sau đó là giá trị.

Ví dụ:

Để gán giá trị 10 cho một biến có tên 'tuổi', ta chỉ cần viết `tuổi = 10` (Trong lập trình bình thường thì không nên viết có dấu như này nha, mà thay vào đó nên viết là `tuoi = 10` hoặc `age = 10`).

Nếu muốn thay đổi giá trị của biến 'tuổi', ta có thể làm tương tự: `tuoi = 30`. Điều đó được gọi là gán lại (re-assigning).

Bạn luôn luôn nên đặt tên biến để mô tả cho thông tin bạn lưu trữ (Ví dụ như trên, tạo biến `tuoi` để lưu thông tin về tuổi của người dùng chẳng hạn) thay vì chỉ sử dụng một chữ cái như 'A' hoặc 'x'.

### Kiểu dữ liệu (Data type)

Trong khoa học máy tính và lập trình máy tính, [kiểu dữ liệu](https://vi.wikipedia.org/wiki/Ki%E1%BB%83u_d%E1%BB%AF_li%E1%BB%87u) hay đơn giản là kiểu là một thuộc tính của dữ liệu, cho máy tính biết cách lập trình viên định sử dụng dữ liệu. Đây là năm kiểu dữ liệu phổ biến cần nhớ:

* Số nguyên (int): Kiểu dữ liệu này được sử dụng cho các số nguyên. Ví dụ: `int age = 20` hoặc `int size = 10`.
* Chuỗi (string): Kiểu dữ liệu này được sử dụng cho văn bản hoặc chuỗi ký tự. Ví dụ: `string name = "Huy"` hoặc `string sentence = "Ngày đẹp trời là ngày được ngủ nướng"`. Thông thường, một chuỗi luôn được bao quanh bởi dấu ngoặc kép.
* Ký tự (char): Kiểu dữ liệu này được sử dụng cho một chữ cái duy nhất. `char letter = 'a'`.
* Số thực dấu phẩy động (float): Kiểu dữ liệu này được sử dụng cho các số chứa dấu thập phân. Ví dụ: `float number = 3.14`.
* Boolean (bool): Kiểu dữ liệu này chỉ được sử dụng cho True hoặc False (đúng hoặc sai, 0 hoặc 1 theo hệ nhị phân). Ví dụ: `bool flag = True`.

Mỗi biến có một tên, một giá trị và một kiểu. Khi viết:

`int age = 10`

Thì `int` là kiểu của biến (data type), `age` là tên của biến (biến name) và `10` là giá trị (value) của biến đó.

### Toán tử số học (Arithmetic operators)

Trong lập trình, bạn có thể sử dụng các toán tử số học giữa các biến hoặc một số giá trị cụ thể. Phép cộng, phép trừ, phép nhân giống như trong toán học (với phép chia thì hơi khác một chút).

Ví dụ, bạn có thể viết như sau:

- `sum = a + b` -> Lưu tổng của các giá trị `a` và `b` vào biến `sum`.
- `c = d - 7` -> Lưu kết quả của phép trừ vào biến `c`.
- `result = 15 * 3` -> Lưu 45 vào biến `result`.

Có ba "kiểu" phép chia:

- `x = a / b` -> đây là phép chia thực.
- `y = 13 DIV 5` -> đây là phép chia số nguyên và nó sẽ lưu 2 vào biến `y`.
- `z = 13 MOD 5` -> đây là phép chia lấy số dư và nó sẽ lưu 3 vào biến `z`.

### Toán tử quan hệ (Relational operators)

Trong khoa học máy tính, [toán tử quan hệ](https://en.wikipedia.org/wiki/Relational_operator) là một cấu trúc hoặc toán tử ngôn ngữ lập trình, dùng để so sánh 2 toán hạng với nhau. Ví dụ như phép bằng nhau (ví dụ: 5 = 5) và phép bất đẳng thức (ví dụ: 4 > 3).

Kết quả của phép đánh giá là đúng hoặc sai. Các toán tử quan hệ được sử dụng cho branching (ở phần trên).

Danh sách các phép toán tử bao gồm: bằng (==), không bằng (≠), lớn hơn (>), nhỏ hơn (<), lớn hơn hoặc bằng (≥), nhỏ hơn hoặc bằng (≤).

### Các phép toán Boolean

Các phép toán Boolean bắt nguồn từ [đại số Boole](https://vi.wikipedia.org/wiki/%C4%90%E1%BA%A1i_s%E1%BB%91_Boole) (Boolean algebra), trong đó các giá trị của các biến là đúng hoặc sai (1 hoặc 0). Để đơn giản hóa lại, có ba phép toán chính mà bạn cần biết:

* AND (VÀ): Kết quả của phép toán này chỉ đúng khi cả hai điều kiện đều đúng, nếu không thì sai (Thường kí hiệu là `&&`).
* OR (HOẶC): Kết quả của phép toán này là đúng khi một trong hai điều kiện đúng (Thường kí hiệu là `||`).
* NOT (KHÔNG): Phép toán này đảo ngược giá trị của điều kiện. Nếu điều kiện đúng thì phép phủ định sẽ cho kết quả là sai và ngược lại.

Các phép toán Boolean cũng chủ yếu được sử dụng cho branching và có thể kết hợp với các toán tử quan hệ. Ví dụ, nếu bạn có một nhiệm vụ cần kiểm tra xem số đó có nhỏ hơn 50 hay không và không phải là 7 thì nó trong code sẽ kiểu như thế này:

```
nếu (số < 50 && số != 7) {
	in_ra_console(số);
}
```

Vậy là xong. Nếu bạn đã hiểu mọi thứ đến giờ, bạn có thể nói rằng BÂY GIỜ BẠN có thể tư duy như một lập trình viên. Đây là kiến thức tối thiểu bạn cần biết để bắt đầu lập trình. Đây là nền tảng mà bạn xây dựng ngày càng nhiều kiến thức. Bạn có thể nhận thấy rằng chúng ta không bắt đầu với bất kỳ ngôn ngữ lập trình nào. Đó là vì mọi thứ ở trên có thể áp dụng cho hầu hết các ngôn ngữ lập trình. Bây giờ, khi bạn hiểu được nền tảng, bạn có thể dễ dàng bắt đầu với bất kỳ ngôn ngữ lập trình nào.

### Các bước tiếp theo

Bây giờ bạn có thể chọn một ngôn ngữ lập trình và học cú pháp của nó. Một số điểm khởi đầu:

- [CS50 Vietsub](https://www.youtube.com/playlist?list=PLjj8gpaW-Tn8QOw7HPrDsl-gQjEGFlkil) - Cá nhân mình không biết là khóa có cập nhật thêm gì mới không. Nếu không bạn có thể học [bản trên kênh Youtube của CS50](https://www.youtube.com/playlist?list=PLhQjrBD2T383q7Vn8QnTsVgSvyLpsqL_R) nha
- [Automate the Boring Stuff with Python](http://automatetheboringstuff.com/) - Đọc miễn phí trên trang của tác giả!
- [Eloquent JavaScript](https://eloquentjavascript.net/) - Một cuốn sách tự học JavaScript

### Credit

Bài viết của tác giả gốc đã bay màu trên Internet nên không có (Chỉ còn [bài trên Reddit](https://old.reddit.com/r/learnprogramming/comments/pxg54p/how_to_start_programming_from_zero/) thôi).
