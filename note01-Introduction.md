# Note01 Introduction
Python là một ngôn ngữ lập trình, nó được tạo ra bởi Guido và Rossum, và phát hành năm 1991.

Tên gọi Python xuất phát từ tên của một chương trình truyền hình là "Monty Python's Flying Circus", một chương trình yêu thích của 2 người sáng lập ra python.

Để thực thi được một chương trình python bạn phải cài đặt một chương trình để dịch nó cho máy tính hiểu, đó là Python Interpreter. Một số máy window và mac đã cài sẵn python trên máy, bạn có thể kiểm tra bằng câu lệnh:
    
    python --version

## Python Syntax
### Python Indentation (thụt lề)
Trong khi ở các ngôn ngữ lập trình khác, việc thụt lề trong mã chỉ nhằm mục đích dễ đọc thì việc thụt lề trong Python rất quan trọng. Python sử dụng thụt lề để biểu thị một khối code.

Số lượng khoảng trắng tùy thuộc vào bạn, cách sử dụng phổ biến nhất là bốn khoảng trắng, nhưng ít nhất phải có một, ví dụ:
```python
if 5 > 2:
 print("Five is greater than two!") 
if 5 > 2:
        print("Five is greater than two!") 

```

### Comments
Sử dụng dấu `#` để comment 1 dòng code hoặc khi ta muốn chú thích gì đó
```python
#This is a comment.
#print("Hello, World!")
print("Hello, World!") #This is a comment
```
Chúng ta cũng có thể sử dụng dấu `"""`để viết chú thích nhiều dòng cho mã, khi thông dịch python vẫn sẽ đọc nội dung nhưng sẽ bỏ qua chúng.
```python
"""
This is a comment
written in
more than just one line
"""
print("Hello, World!")
```
### Variable
Trong Python không cần phải khai báo kiểu dữ liệu cho biến, và có thể gán các giá trị với kiểu dữ liệu khác nhau cho cùng 1 biến:
```python
x = 4 # x is of type int
x = "Sally" # x is now of type str
print(x)
```
Chuỗi có thể được sử dụng dấu "" hoặc ''

sử dụng hàm `type(paramator)`để kiểm tra kiểu biến của paramator
#### Variable Name
Một số quy tắc khi đặt tên biến:
- Tên biến chỉ có thể chứa các ký tự, các
- Tên biến phải bắt đầu bằng ký tự hoặc dấu `_`, không được bắt đầu bằng số.
- Tên biến phân biệt chữ hoa và chữ thường, ví dụ abc khác aBc, khác aBC...
- Tên biến không được trùng với [python keywords](https://www.w3schools.com/python/python_ref_keywords.asp)

Đối với biến có nhiều từ ví dụ `first name`, chúng ta có 3 kiểu viết sau:
- camel case: firstName
- pascal case: FirstName
- snake case: first_name

Khai báo nhiều biến trên 1 dòng
```python
# gán nhiều biến cho các giá trị
x, y, z = "Orange", "Banana", "Cherry"

# gán nhiều biến cho cùng 1 giá trị
x = y = z = "Orange"

# sử dụng kỹ thuật unpacking
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
```
#### Variable Scope
Mỗi biến đều có phạm vi hoạt động của nó dựa vào vị trí khai báo của nó, những biến được khai báo ngoài các function được gọi là các global varialbe và có thể sử dụng ở mọi nơi. Còn những biến được khai báo bên trong function sẽ được gọi là các local variable, những biến này chỉ có thể sử dụng bên trong các function.

Bạn cũng có thể đưa một local variable thành một global varialbe bằng câu lệnh global


