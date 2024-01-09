# Python Function
Function là một đoạn code chịu trách nhiệm xử lý một nhiệm vụ nào đó, nó sẽ thực thi khi được gọi.
cú pháp để khai báo python function
```python
# cú pháp khai báo một python function đơn giản
def function_name(par1, par2){
  return par1 + par2;
}
# gọi function
function_name(1, 2) # kết quả trả về là 3
```
Arguments và Paramaters: 
- paramater là khi mà bạn định nghĩa function(par1, par2 chính là các paramaters)
- argument là khi mà bạn gọi function (1,2 chính là các arguments)

Python cho phép bạn linh động trong việc khai báo số lượng các paramator khi khai báo biến kỹ thuật đó gọ là Arbitrary Arguments, ví dụ:
```python
function_name(arg*){

}
# bạn có thể gọi như sau
my_function(1,2,3,4,5);
```
Bạn cũng có thể linh động trong việc truyền các argument trong lúc gọi function mà không cần nhớ thứ tự của chúng, kỹ thuật này gọi là Keyword Arguments, ví dụ
```python
def my_function(arg1, arg2, arg3) {}

# gọi function với keyword argument, 2 cách gọi dưới đây là tương đương nhau
my_function(arg2=1, arg1=5, arg3=6)
my_function(5,1,6)

```
Ngoài ra để hỗ trợ việc bạn quên, Python còn cung cấp cho bạn 1 kỹ thuật nữa đó là Arbitrary Keyword Arguments, **kwargs, nó kết hợp cả 2 kỹ thuật mà ta nói ở trên:
```python
def my_function(**my_var){}

my_function(var1 = "", var2="");
```

## Lambda
lamda là những function không có tên

Hàm lambda có thể nhận bất kỳ số lượng đối số nào nhưng chỉ có thể có một biểu thức().
cú pháp: lambda arguments : expression

