# Python Operators (Toán Tử Trong Python)

## Python Arithmetic Operators (Toán tử số học)
```python
# Toán tử số học được dùng để tính toán các phép toán thông thường
# Toán tử số học gồm 7 phép cơ bản: cộng, trừ, nhân, chia, chia lấy nguyên, chia lấy dư, lũy thừa
x,y=6,8
z = x + y
z = x - y
z = x * y
z = x / y
z = x % y
z = x // y
z = x * y
```
## Python Bitwise Operators (Toán tử bitwise)
```python

```
## Python Assignment Operators (Toán tử gán)

## Python Comparison Operators (Toán tử so sánh)
```python
# Bao gồm 6 toán tử so sánh (==, !=, >, <, >=, <=)
# kết quả trả về là một giá trị bool
x,y = 6, 8
print(x == y) #False
print(x != y) #True
print(x > y) #False
print(x < y) #True
print(x >= y) #False
print(x <= y)  #True
```
## Python Logical Operators
```python
# Toán tử logic được sử dụng để kết hợp các câu lệnh có điều kiện
# Kết quả trả về là một giá trị bool
x,y = 6,8
print(x < 5 and  x < 10) # return False 
print(x < 5 or x < 4) # return False
print(not(x < 5 and x < 10) # return True
```

## Độ ưu tiên của các toán tử
Độ ưu tiên của các toán tử theo thứ tự sau: 
1. dấu ngoặc đơn `()`
2. phép lũy thừa `**`
3. `+x  -x  ~x`
4. các phép nhân chia: `*  /  //  %`
5. phép cộng trừ `+  -`
6. dịch chuyển trái và phải theo bit: ``<<  >>
7. Phép AND
8. phép XOR
9. phép OR
10. các toán tử so sánh `==`, `!=  >  >=  <  <=  is  is not  in  not in`
11. toán tử NOT `not`
12. toán tử AND `and`
13. toán tử OR `or`
