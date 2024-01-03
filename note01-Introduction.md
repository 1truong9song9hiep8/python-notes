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



