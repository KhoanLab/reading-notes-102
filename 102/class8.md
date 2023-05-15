# Read: 08 - Operators and Loops

1. What is an expression in JavaScript?

   - Một biểu thức trong JavaScript là bất kỳ đoạn mã nào đánh giá thành một giá trị. Điều này có thể bao gồm các giá trị (như số hoặc chuỗi), biến, toán tử và các lời gọi hàm. Biểu thức có thể kết hợp với các toán tử để tạo ra các biểu thức phức tạp hơn, sau đó có thể được sử dụng trong các lệnh gán hoặc các lệnh khác. Ví dụ, 2 + 3 là một biểu thức đánh giá thành giá trị 5, và myVar * 4 là một biểu thức nhân giá trị của biến myVar với 4.

   - An expression in JavaScript is any piece of code that evaluates to a value. This can include values (such as numbers or strings), variables, operators, and function calls. Expressions can be combined with operators to create more complex expressions, which can then be used in assignments or other statements. For example, 2 + 3 is an expression that evaluates to the value 5, and myVar * 4 is an expression that multiplies the value of the variable myVar by

2. Why would we use a loop in our code?

   - Chúng tôi sử dụng các vòng lặp trong mã của mình để thực thi lặp đi lặp lại một khối mã cho đến khi đáp ứng một điều kiện cụ thể. Điều này có thể hữu ích trong các tình huống khi chúng ta cần thực hiện các thao tác giống nhau hoặc tương tự nhiều lần với các giá trị khác nhau hoặc khi chúng ta cần lặp lại một tập hợp dữ liệu. Vòng lặp có thể tiết kiệm thời gian và giảm số lượng mã chúng ta cần viết, vì chúng ta có thể thực hiện các thao tác trên nhiều mục mà không phải viết mã riêng cho từng mục. Các loại vòng lặp phổ biến trong JavaScript bao gồm vòng lặp for, vòng lặp while và vòng lặp do-while.

   - We use loops in our code to execute a block of code repeatedly until a specific condition is met. This can be useful in situations where we need to perform the same or similar operations multiple times with different values, or when we need to iterate over a collection of data. Loops can save time and reduce the amount of code we need to write, as we can perform operations on multiple items without having to write separate code for each one. Common types of loops in JavaScript include for loops, while loops, and do-while loops.

3. When does a for loop stop executing?

   - Vòng lặp for trong JavaScript dừng thực thi khi điều kiện vòng lặp trở thành sai. Điều kiện vòng lặp được đánh giá ở đầu mỗi lần lặp của vòng lặp và nếu nó sai, vòng lặp sẽ không thực hiện lại. Điều kiện thường dựa trên một biến đếm được khởi tạo ở đầu vòng lặp và tăng hoặc giảm với mỗi lần lặp. Vòng lặp sẽ tiếp tục thực hiện khi điều kiện còn đúng và sẽ dừng khi điều kiện sai.

   - A for loop in JavaScript stops executing when the loop condition becomes false. The loop condition is evaluated at the beginning of each iteration of the loop, and if it is false, the loop will not execute again. The condition is typically based on a counter variable that is initialized at the beginning of the loop and incremented or decremented with each iteration. The loop will continue to execute as long as the condition is true, and will stop when the condition becomes false.

4. How many times will a while loop execute?

   - Vòng lặp while sẽ thực hiện lặp đi lặp lại miễn là điều kiện được chỉ định trong câu lệnh while được đánh giá là đúng. Do đó, số lần vòng lặp while sẽ thực thi tùy thuộc vào điều kiện cụ thể được đánh giá và số lần nó đánh giá là đúng. Nếu điều kiện không bao giờ đúng, vòng lặp sẽ không thực hiện. Nếu điều kiện luôn đúng, vòng lặp sẽ thực hiện vô thời hạn, được gọi là vòng lặp vô hạn.

   - A while loop will execute repeatedly as long as the condition specified in the while statement evaluates to true. Therefore, the number of times a while loop will execute depends on the specific condition being evaluated and how many times it evaluates to true. If the condition is never true, the loop will not execute at all. If the condition is always true, the loop will execute indefinitely, which is known as an infinite loop.



// TRUTHTABLE!!!

// console.log(3 === '3') // Data type

// Logical AND / T && T
// console.log(true && false && true && false) // false
// Truong DH 1: Tot nghiep 12 && Thi > 20
//                    true          19 > 20
//                    true  &&        false  

// console.log (false && false) // false
//              false       &&     false
//                          flase

// console.log(!true); // 

// Logical OR / T || F
// console.log(true || false || false || true); // true
// Truong DH 2: Tot nghiep 12 || Thi > 20
//                 T        ||    F
//                 F        ||     T

// let myName = 'Hung'; // 
// console.log(myName == 'Khoan' || myName == 'Hoa'); 
// //                  F                  F

// console.log(myName == 'Khoan' && myName == 'Hoa' && myName == 'Hung' && myName == 'Nhat');
//                 T                    F

// console.log(true == !false);
//            true == true
//                  true

// console.log(!(5 == '5') == (5 === '5')); // false
//               F      ==      F
//                     T


//While loop
// while(condition TRUE){
//    excute code
//}

// let userName = prompt('What is your name?'); // ''

// while(userName == ''){ // True // false
//   userName = prompt('No really, tell me your name...');
// }

// console.log(userName);


// let num = 0;

// while(num < 10){ // true
//   num++; // num += num
//   console.log(num);
// }

// 0 | 0 < 10 ? T | excute num = 1;
// 1 | 1 < 10 ? T | excute num = 2;
// 2 | 2 < 10 ? T | excute num = 3;
// ...
// 8 | 8 < 10 ? T | excute num = 9;
// 9 | 9 < 10 ? T | excute num = 10;
// 10 | 10 < 10 ? F | break;

// For
// for(init value; condition to evaluate ; increment)

// for(let i = 1; i <= 10; i = i * 5){
//   console.log(i*2);
// }

// 0 | 0 < 10 ? T excute  | log(i) = 0 | i = i + 1
// 1 | 1 < 10 ? T | excute: log(i) = 1 | i = 2
// 2 | 2 < 10 ? T | excute: log(i) = 2 | i = 3
// ...
// i = 9 | 9 < 10 ? T | excute: log(i) = 9 | i = 10
// i = 10 | 10 < 10 ? F | break.


// i = 0 | 0 <= 10 ? T | excute | log(i) = 0 | i = i + 5 // 0 + 5 // i = 5
// i = 5 | 5 <= 10 ? T | excute | log(i) = 5 | i = i + 5 // 5 + 5 = 10
// i = 10 | 10 <= 10 ? T | excute | log(i) = 10 | i = i + 5 // 10 + 5 = 15

// i = 0 | 0 <= 10 ? T | excute | log(i*2) = 0*2 = 0 | i = i * 5 // 0 + 5 = 5
// i = 5 | 5 <= 10 ? T | excute | log(i*2) = 5*2 = 10 | i = i + 5 // 5 + 5 = 10
// i = 10 | 10 <= 10 ? T | excute | log(i*2) = 10*2 = 20 | i = i + 5 // 15 
// i = 15 | 15 <= 10 ? F | break
