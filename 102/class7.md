# Read: 07 - Programming with JavaScript

1. What is control flow?

  - Luồng điều khiển (control flow) đề cập đến thứ tự các câu lệnh hoặc hướng dẫn trong một chương trình được thực thi. Trong hầu hết các ngôn ngữ lập trình, các câu lệnh được thực thi lần lượt theo thứ tự xuất hiện trong mã. Tuy nhiên, các cấu trúc luồng điều khiển như câu lệnh điều kiện (if/else) và vòng lặp (for/while) có thể thay đổi luồng thực thi bình thường dựa trên các điều kiện hoặc tiêu chí nhất định. Luồng điều khiển là cần thiết để tạo ra các chương trình phức tạp có thể thực hiện các hành động khác nhau tùy thuộc vào điều kiện cụ thể và để tự động hóa các nhiệm vụ lặp lại.

2. What is a JavaScript function?

  - Một hàm JavaScript là một khối mã thực hiện một nhiệm vụ cụ thể và có thể được thực thi khi nó được gọi hoặc triệu gọi. Hàm được sử dụng để chia nhỏ một chương trình thành các phần mã nhỏ hơn, dễ quản lý và có thể sử dụng lại được. Chúng có thể lấy tham số đầu vào (arguments) và trả về một giá trị hoặc thực hiện một hành động cụ thể. Trong JavaScript, các hàm là các đối tượng có thứ bậc đầu tiên, điều đó có nghĩa là chúng có thể được gán cho các biến, truyền vào như là tham số cho các hàm khác hoặc được trả về từ các hàm. Hàm có thể được khai báo bằng cách sử dụng từ khóa function hoặc sử dụng arrow functions, là cú pháp ngắn hơn được giới thiệu trong ES6.

  - A JavaScript function is a block of code that performs a specific task and can be executed when it is called or invoked. Functions are used to break down a program into smaller, more manageable and reusable pieces of code. They can take input parameters (arguments) and return a value or perform a specific action. In JavaScript, functions are first-class citizens, which means they can be assigned to variables, passed as arguments to other functions, or returned from functions. Functions can be declared using the function keyword or using arrow functions, which are a shorter syntax introduced in ES6.

3. What does it mean to invoke - or call - a function?

  - Khi gọi hoặc thực thi một hàm có nghĩa là thực hiện mã được định nghĩa bên trong hàm. Khi một hàm được gọi, chương trình nhảy đến dòng mã đầu tiên bên trong hàm và thực thi từng dòng mã cho đến khi đến cuối hàm hoặc một lệnh return. Để gọi một hàm, bạn cần sử dụng tên hàm theo sau bởi dấu ngoặc đơn, và bạn có thể truyền đối số cho hàm trong ngoặc đơn. Sau đó, hàm sẽ thực thi với các đối số được cung cấp và trả về kết quả, nếu có.
  - To invoke or call a function means to execute the code that is defined within the function. When a function is called, the program jumps to the first line of code within the function and executes each line until it reaches the end of the function or a return statement. In order to call a function, you need to use the function name followed by parentheses, and you may pass arguments to the function within the parentheses. The function will then execute with the provided arguments and return the result, if any.

4. What are the parenthesis () for when you define a function?
  - Dấu ngoặc đơn () trong định nghĩa hàm trong JavaScript được sử dụng để chỉ định các tham số hoặc giá trị đầu vào mà hàm sẽ chấp nhận khi nó được gọi. Các tham số được liệt kê bên trong dấu ngoặc đơn, được phân tách bằng dấu phẩy. Ví dụ, trong định nghĩa hàm function addNumbers(x, y) { ... }, dấu ngoặc đơn (x, y) chỉ định rằng hàm chấp nhận hai tham số, x và y. Khi hàm được gọi, các giá trị có thể được truyền dưới dạng đối số cho các tham số này, như sau: addNumbers(2, 3).
  - The parentheses () in a function definition in JavaScript are used to specify the parameters, or input values, that the function will accept when it is called. The parameters are listed inside the parentheses, separated by commas. For example, in the function definition function addNumbers(x, y) { ... }, the parentheses (x, y) specify that the function accepts two parameters, x and y. When the function is called, values can be passed as arguments for these parameters, like this: addNumbers(2, 3).

