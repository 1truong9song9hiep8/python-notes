# Python Collections
Một số thuật ngữ:
- odered: thứ tự các phần tử trong tập hợp là không đổi và có thể truy cập dựa vào index hoặc key.
- changeble: có thể thêm, xóa, thay đổi phần tử sau khi tạo.

## 1. List
- Sử dụng `[]`để khai báo list trong python.
- Các items trong list là odered, changeble, cho phép chứa giá trị trùng lặp và có thể chứa các kiểu dữ liệu khác nhau.
  ột số hoạt động với list:
  ```python
  list = ["apple", "banana", "cherry"]

  # truy cập vào item bằng index
  fruit = list[0] # apple
  fruit = list[1] # banana

  #truy cập item bằng index âm, lúc này -1 sẽ là item cuối cùng, và -2 là kế cuối...
  fruit = list[-1] #cherry
  fruit = list[-3] #apple

  # lấy ra một tập các item dựa vào dải index (tính từ index đầu đến index kế của cuối)
  # he search will start at index 2 (included) and end at index 5 (not included).
  thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
  print(thislist[2:5]) #
  print(thislist[:5]) # lấy từ đầu đến item 4
  print(thislist[2:]) # lấy item từ index = 2 đến hết

  # Kiểm tra trong list có item nào không
  if "apple" in thislist:
    print("Yes, 'apple' is in the fruits list")

  # change list item
  thislist = ["apple", "banana", "cherry"]
  thislist[1] = "blackcurrant"
  print(thislist)

  # chang list item
  thislist = ["apple", "banana", "cherry", "orange", "kiwi", "mango"]
  thislist[1:3] = ["blackcurrant", "watermelon"]
  print(thislist)
  
  ```
  ### List Comprehension
  List Comprehension là cú pháp ngắn gọn hơn để bạn có thể tạo một list mới từ 1 list có sẵn
  ```python
  # Cú pháp của list comprehension: newlist = [expression for item in iterable if condition == True]
  ```
## Tuple
Tuple là một tập hợp: **ordered**, **unchangeable**, **cho phép trùng lặp dữ liệu**.<br>
Tuple được khai báo bằng dấu `()`
