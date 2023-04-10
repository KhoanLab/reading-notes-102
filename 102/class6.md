Read: 06 - Dynamic web pages with JavaScript

1. What are variables in JavaScript?

    - Trong JavaScript, biến là một container (thùng chứa) chứa một giá trị, có thể là bất kỳ kiểu dữ liệu nào, như chuỗi, số hoặc boolean. Biến được sử dụng để lưu trữ và thao tác dữ liệu trong các chương trình.

    - Trong JavaScript, biến có thể được khai báo bằng các từ khóa let, const hoặc var. Từ khóa let được sử dụng để khai báo biến có thể được gán lại giá trị, trong khi từ khóa const được sử dụng để khai báo biến không thể được gán lại giá trị. Từ khóa var là cách khai báo biến cũ hơn có một số khác biệt về phạm vi và hành vi so với let và const.

    In JavaScript, a variable is a container that holds a value, which can be of any data type, such as a string, number, or boolean. Variables are used to store and manipulate data in programs.

    In JavaScript, variables can be declared using the let, const, or var keywords. The let keyword is used to declare variables that can be reassigned, while the const keyword is used to declare variables that cannot be reassigned. The var keyword is an older way of declaring variables that has some differences in scope and behavior compared to let and const.

2. What does it mean to declare a variable?

    - Để khai báo một biến trong lập trình có nghĩa là tạo ra một tham chiếu có tên trong chương trình để lưu trữ một giá trị của một kiểu dữ liệu cụ thể. Khi một biến được khai báo, chương trình sẽ dành một vùng nhớ để lưu trữ giá trị của biến đó. Thông thường, việc khai báo biến bao gồm chỉ định một tên cho biến và chỉ định kiểu dữ liệu của nó. Trong một số ngôn ngữ lập trình, chẳng hạn như JavaScript, biến có thể được khai báo bằng các từ khóa như let, const, hoặc var. Việc khai báo biến là bước cần thiết trước khi gán một giá trị cho nó hoặc sử dụng nó trong các phần khác của chương trình.

    - To declare a variable means to create a named reference in a program that can be used to store a value of a particular data type. When a variable is declared, the program reserves a space in memory to hold the value of the variable. Declaring a variable typically involves specifying a name for the variable and indicating its data type. In some programming languages, such as JavaScript, variables can be declared using keywords like let, const, or var. Declaring a variable is a necessary step before assigning a value to it or using it in other parts of the program.

3. What is an “assignment” operator, and what does it do?

    - "Assignment" operator là một loại toán tử được sử dụng trong các ngôn ngữ lập trình để gán giá trị cho một biến. Trong nhiều ngôn ngữ lập trình, dấu "=" được sử dụng làm toán tử gán. Khi sử dụng toán tử gán, giá trị ở phía bên phải của toán tử được gán cho biến ở phía bên trái. Ví dụ, trong câu lệnh "x = 10;", giá trị 10 được gán cho biến "x". Toán tử gán thường được sử dụng để khởi tạo biến, cập nhật giá trị và thực hiện các hoạt động khác yêu cầu lưu trữ dữ liệu trong biến.

    - What is an "assignment" operator, and what does it do?
An "assignment" operator is a type of operator used in programming languages to assign a value to a variable. In many programming languages, the "=" sign is used as the assignment operator. When an assignment operator is used, the value on the right-hand side of the operator is assigned to the variable on the left-hand side. For example, in the statement "x = 10;", the value 10 is assigned to the variable "x". Assignment operators are commonly used to initialize variables, update values, and perform other operations that require storing data in variables.

4. What is information received from the user called?

    - Thông tin nhận được từ người dùng thường được gọi là "đầu vào" (input). Trong lĩnh vực máy tính, đầu vào có thể là bất kỳ dữ liệu hay thông tin nào được nhập vào hệ thống máy tính, bằng cách sử dụng bàn phím, chuột, hoặc các thiết bị khác. Đầu vào có thể có nhiều dạng khác nhau, bao gồm văn bản, số, lệnh và các loại dữ liệu khác. Khi nhận được đầu vào, hệ thống máy tính có thể xử lý nó theo nhiều cách khác nhau, chẳng hạn như lưu trữ nó trong bộ nhớ, thao tác với phần mềm, hoặc hiển thị nó trên màn hình.

    - Information received from the user is generally referred to as "input". In computing, input can be any data or information that is entered into a computer system, either by a person or by another program or device. This input can take many forms, including text, numbers, commands, and other types of data. Once input is received, a computer system can process it in various ways, such as storing it in memory, manipulating it with software, or displaying it on a screen.

# Demo

`
let a = 1;
let b = 2;
let c = a + b;

// variables - containers for storing data
console.log(a);
console.log(c);
console.log('Hello World!');

// variables can be declared 4 ways
// const --> constant, can't be changed
// let --> changeable value
// var --> old way, don't do this
// {none} --> don't worry about this for now

const myName = 'Khoan';
console.log(myName);


let myFavColor = 'yellow';
console.log(myFavColor);
myFavColor = "blue";
console.log(myFavColor);

// DATA TYPES
// strings --> 'text' or "text" or '2' or "2"
// numbers/integers --> 2 or 42 or 123123
// boolean --> true or false


console.log('Hello World!');
console.log(42);
console.log(42 + 9);

// Useful functions
// console.log() --> print infomation to the console
// alert() --> give us a popup box
// prompt() --> how you can get info from the user
// document.write() --> how you will put content on your website


// CONDITIONAL LOGIC (if/else if/else)
let userName = prompt('What is your name?');
userName = userName.toLowerCase();

if (userName == "Khoan") {
  alert('Hiya teach!');
  console.log('I am in the if-statement');
} else if (userName == 'bEN') {
  alert("TA's are some");
} else {
  alert('Hello and welcome, class');
}

// OPERATORS

let myNumber = 42;

console.log(myNumber == '42');
console.log(myNumber === 42);
console.log(myNumber === '42');

let reponse = prompt('Do you like cookies?')

if (response = 'yes') {
  alert("you're come to the right place!");
} else if (response = 'no') {
  alert("what are you doing at a cookie shop website?")
} else {
  alert("i'm not sure what that means....");
}

let value = 2 + '2';
console.log(typeof (value));
`
