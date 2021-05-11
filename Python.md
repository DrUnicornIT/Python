---


---

<h1 id="python-variable--types">Python Variable  Types</h1>
<h2 id="values-to-variables">Values to Variables</h2>
<p>Python hỗ trợ nhận biết dạng cấu trúc dữ liệu của người dùng mà không cần phải khai báo</p>
<pre><code>counter = 100 # Một giá trị số nguyên (int)
miles = 1000.0 # Một giá trị số thập phân (float)
name = "John" # Một string
</code></pre>
<p>Ta có thể đa dạng hóa phương thức nhập dữ liệu</p>
<pre><code>a = b = c = 1
a, b, c = 1, 2, "John"
</code></pre>
<h2 id="python-number">Python Number</h2>
<p>Dữ liệu số được tạo ra khi ta gán cho biến 1 giá trị ban đầu</p>
<pre><code>val1 = 1
val2 = 2
</code></pre>
<p>Ta có thể xóa biến này đi ( sau dòng đấy những biến sẽ được coi như chưa bị khai báo )</p>
<pre><code>del val1, val2
</code></pre>
<p>Python hỗ trợ 3 loại số khác nhau cơ bản sau :</p>
<ul>
<li>int (số nguyên)</li>
<li>float (số thực)</li>
<li>complex (số ảo)</li>
</ul>
<h2 id="python-string">Python String</h2>
<p>Nó cũng sẽ na ná như string của c++, chỉ có điều cú pháp sẽ đơn gian hơn rất nhiều. Xâu bắt đầu là 0 và kết thúc là -1<br>
<strong>Code</strong></p>
<pre><code>str =  'Hello World!'
print (str)  #  In ra một xâu hoàn chỉnh 
print (str[0])  #  In ra phần tử đầu của xâu đó
print (str[2:5])  #  In ra phần tử  3rd  to  5th 
print  (str[2:])  #  In ra bắt đầu từ phần tử 3rd  
print  (str  * 2)  #  In ra xâu đấy 2 lần
print (str  + "TEST") # In ra xâu đấy thêm từ TEST
</code></pre>
<p><strong>Output</strong></p>
<pre><code>Hello World!
H
llo
llo World!
Hello World!Hello  World!
Hello World!TEST
</code></pre>
<h2 id="python-lists">Python Lists</h2>
<p><strong>List</strong> là cấu trúc dữ liệu ghép linh hoạt nhất trong python. Chuỗi cung như xâu bắt đầu từ 0 và kết thúc bằng -1. Đặc biệt list có thể là mọi loại cấu dạng vừa có thể là int, float, string …<br>
<strong>Code</strong></p>
<pre><code>list =  [ 'abcd',  786  , 2.23,  'john',  70.2 ] 
tinylist =  [123,  'john']
print (list) # In ra lists hoàn trỉnh
print  (list[0]) # In ra phần tử đầu tiên 
print (tuple[1:3])  # In ra phần tử  from 2nd till 3rd 
print  (tuple[2:])  # In ra phần tử from 3rd element 
print  (tinytuple *  2)  # In lập lại 2 lần
print (tuple +  tinytuple) # In ra xâu ghép của 2 xâu
</code></pre>
<p><strong>Output</strong></p>
<pre><code>('abcd', 786, 2.23, 'john', 70.200000000000003)
abcd
(786, 2.23)
(2.23, 'john',  70.200000000000003)
(123, 'john', 123, 'john')
('abcd', 786, 2.23, 'john',  70.200000000000003,  123, 'john')
</code></pre>
<h2 id="python--dictionary">Python  Dictionary</h2>
<p>Python  Dictionary là một loại như mảng băm Hash. Với Key có thể là tất cả các dạng giá trị của python nhưng thường sẽ là xâu. Với mỗi Key sẽ có Values khác nhau.<br>
<strong>Code</strong></p>
<pre><code>   dict = {}
   dict['one'] =  "This is  one" 
   dict[2]  =  "This is  two"
   tinydict =  {'name': 'john','code':6734, 'dept': 'sales'} 
   print  (dict['one'])  # In ra giá trị for 'one' key 
   print  (dict[2])  # In ra giá trị for 2  key
   print (tinydict)  # In ra dữ liệu hoàn chỉnh
   print  (tinydict.keys())  # In ra tất cả các key
   print (tinydict.values()) # In ra tất cả các giá trị
</code></pre>
<p><strong>Output</strong></p>
<pre><code>This is one 
This is two
{'dept': 'sales',  'code':  6734,  'name':  'john'} 
['dept', 'code',  'name']
['sales', 6734, 'john']
</code></pre>
<h1 id="types--of--operator">Types  of  Operator</h1>
<h2 id="arithmetic-operator">Arithmetic Operator</h2>
<p>Là phép toán cộng trừ nhân chia …<br>
<strong>Note</strong></p>
<ul>
<li>Với Lũy thừa là **</li>
<li>Chia lấy dư phần nguyên dưới là //</li>
</ul>
<p><strong>Code</strong></p>
<pre><code>b  =  10
c = 0
c = a + b
print ("Line 1  - Value  of c is  ",  c)
c = a - b
print ("Line 2  - Value  of c is  ",  c )
c = a * b
print ("Line 3  - Value  of c is  ",  c)
c = a / b
print ("Line 4  - Value  of c is  ",  c )
c = a % b
print ("Line 5  - Value  of c is  ",  c)
a  =  2
b  =  3
c = a**b
print ("Line 6  - Value  of c is  ",  c)
a = 10
b = 5
c = a//b
print ("Line 7  - Value  of c is  ",  c)
</code></pre>
<p><strong>Output</strong></p>
<pre><code>Line 1 - Value of c is  31  
Line 2 - Value of c is  11
Line 3 - Value of c is  210  
Line 4  - Value of c is  2.1  
Line 5 - Value of c is  1 
Line 6 - Value of c is  8
Line 7 - Value of c is  2
</code></pre>
<h2 id="comparison--operators">Comparison  Operators</h2>
<p>Là những phép so sánh &gt;, &lt;. ==, !=, &lt;=, &gt;=<br>
<strong>Code</strong></p>
<pre><code>a =  21
b =  10
if ( a == b ):
    print ("Line  1  -  a  is  equal  to  b") 
else:
    print ("Line 1  - a is  not equal  to  b")
if ( a != b ):
    print ("Line  2  -  a  is  not  equal  to  b") 
else:
    print ("Line 2  - a is  equal  to  b")
if ( a &lt; b ):
    print ("Line  3  -  a  is  less  than  b"  ) 
else:
    print ("Line 3  - a is  not less  than  b")
if ( a &gt; b ):
    print ("Line  4  -  a  is  greater  than  b") 
else:
    print ("Line 4  - a is  not greater than  b")
    
a,b = b,a #values  of  a  and  b  swapped.  a  becomes  10,  b  becomes  21 

if ( a &lt;= b ):
    print ("Line  5  -  a  is  either  less  than  or  equal  to  b") 
else:
    print ("Line 5  - a is  neither less  than  nor  equal to  b")
if ( b &gt;= a ): 
    print ("Line  6  -  b  is  either  greater  than  or  equal  to  b") 
else:
    print ("Line 6  - b is  neither greater than  nor equal to b")
</code></pre>
<p><strong>Output</strong></p>
<pre><code>Line 1 - a is not equal to b 
Line  2 - a is not equal to b 
Line  3 - a is not less than b 
Line  4 - a is greater than b
Line 5 - a is either less than or equal to  b
Line 6 - b is either greater than  or equal to b
</code></pre>
<h2 id="assignment-operators">Assignment Operators</h2>
<p>Là những phép toán bắc cầu như là +=, -=,*=, /=, //=, %=, **=<br>
<strong>Code</strong><br>
a  =  21<br>
b  =  10<br>
c = 0<br>
c = a + b<br>
print ("Line 1  - Value  of c is  ",  c)<br>
c += a<br>
print ("Line 2  - Value  of c is  ",  c )<br>
c *= a<br>
print ("Line 3  - Value  of c is  ",  c )<br>
c /= a<br>
print ("Line 4  - Value  of c is  ",  c )<br>
c  =  2 c %=  a<br>
print ("Line 5  - Value  of c is  ",  c)<br>
c **= a<br>
print ("Line 6  - Value  of c is  ",  c)<br>
c //=  a<br>
print ("Line 7  - Value  of c is  ",  c)</p>
<p><strong>Output</strong></p>
<pre><code>Line 1 - Value of c is  31 
Line  2 - Value of c is  52 
Line  3 - Value of c is  1092  
Line  4 - Value of c is  52.0  
Line  5 - Value of c is  2
Line 6 - Value of c is  2097152
Line 7 - Value of c is  99864
</code></pre>
<h2 id="bitwise--operators">Bitwise  Operators</h2>
<p>Là một số phép toán trên dãy BIT ( giống như ở c++)<br>
bin(val) = 0101010 : lệnh để chuyển số val thành dãy BIT</p>
<h2 id="decision--making">Decision  Making</h2>
<p>Là câu lệnh if else như bên c++</p>
<p><strong>Code</strong></p>
<pre><code>var1 = 100
if var1:
    print ("1  -  Got  a  true  expression  value") print (var1)
var2 = 0 
if var2:
    print ("2  -  Got  a  true  expression  value") print (var2)
print ("Good bye!")
</code></pre>
<p><strong>Output</strong></p>
<pre><code>1 -  Got  a  true  expression  
value 100
Good bye!
</code></pre>
<h2 id="loops">Loops</h2>
<p>câu lệnh while tương tự như c++<br>
<strong>Code</strong></p>
<pre><code>while (expression): 
    statement(s)
</code></pre>
<p>Ví Dụ<br>
<strong>Code</strong></p>
<pre><code>count = 0
while (count &lt;  9):
    print ('The count is:',  count)
    count =  count  + 1
print ("Good bye!")
</code></pre>
<p><strong>Output</strong></p>
<pre><code>The count is: 0 
The count is: 1 
The count is: 2 
The count is: 3
The count is: 4
The count  is: 5 
The count is: 6
The count is: 7 
The count is: 8
Good bye!
</code></pre>
<h2 id="loop-statements">Loop Statements</h2>
<p>Đây là vòng lập gọi ra các giá trị của một list hay một string<br>
<strong>Code</strong></p>
<pre><code>for (iterating_var in  sequence): 
statements(s)
</code></pre>
<p>Ví dụ</p>
<ul>
<li>range(n) xây dựng mảng từ 0 đến n - 1</li>
</ul>
<p><strong>Code</strong></p>
<pre><code>for var in list(range(5)): 
	print (var)
for letter in 'Python':  # traversal of a string sequence 
    print ('Current Letter :', letter)
print()
fruits = ['banana', 'apple',  'mango']
for fruit  in fruits:  # traversal of List sequence 
    print ('Current fruit :',  fruit)
    
for  index  in range(len(fruits)) :
    print ('Current fruit :',  fruits[index])
print ("Good bye!")
</code></pre>
<p><strong>Output</strong></p>
<pre><code>0
1
2
3
4
Current Letter : P 
Current Letter : y
Current Letter : t 
Current Letter : h
Current Letter : o 
Current Letter : n
Current fruit : banana 
Current fruit : apple 
Current fruit : mango 
Current fruit : banana 
Current fruit : apple 
Current fruit : mango 
Good bye!
</code></pre>
<p><strong>Note</strong></p>
<ul>
<li>Các câu lệnh break if continue giống C ++</li>
</ul>
<h1 id="tạo-hàm-tùy-chỉnh-trong-python">Tạo hàm tùy chỉnh trong Python</h1>
<p>Giống như cách gán một giá trị cho một biến, một đoạn logic cũng có thể được liên kết với một tên bằng cách định nghĩa nó là một hàm<br>
<strong>Code</strong></p>
<pre><code>def square(x):
    return x * x
print(square(5))
</code></pre>
<p>**Output</p>
<pre><code>25
</code></pre>

