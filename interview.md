# A. THÔNG TIN CHUNG

### Câu 1: Giới thiệu bản thân

- Tên tuổi: Ngô Đăng Quang - 22 Tuổi
- Sinh viên Đại học khoa học Tự Nhiên, Khoa Công Nghệ Thông Tin
- Sở thích: Yêu thích các môn thể thao vận động mạnh như bóng chuyền, đá bóng và võ thuật. Ngoài ra em cũng yêu thích code web Frontend tại vì em có thể tạo ra những sản phẩm đẹp theo ý thích của bản thân.
- Định hướng làm việc của em: Trong thời gian tới em sẽ làm thiên về Frontend Development, tương lai xa hơn em muốn trở thành một Fullstack Development

### Câu 2: Tại sao lại muốn apply vào công ty này?

- Em biết GEEK Up là một công ty chuyên làm Product, là một products partner với những doanh nghiệp lớn như VP Bank, Viettel, Elsa và các công ty nước ngoài nữa.
- Công ty cũng thành lập được khoảng 9 năm, nhưng mang tinh thần của một start up, và một công ty start up sẽ giúp em học được nhiều hơn là những công ty OutSource.
- Ở GEEK Up hoạt động theo mô hình Flag, không phân cấp nên trong quá trình làm việc mọi người có thể thoải mái hơn, giúp luyện kỹ năng Self management tốt nhất.
- Em cũng đã có một khoảng thời gian là 10 tuần để thực tập tại công ty, em yêu thích con người và môi trường làm việc ở đây. Nên em muốn apply vào công ty để được làm việc cùng với mọi người ở đây.

### Câu 3: Em apply vào vị trí JS, React thì em làm JS được bao lâu rồi?

- Em bắt đầu học về Javascript và React khoảng từ đầu năm nay.

# B. HTML / CSS

### Câu 1: Đã từng làm việc với HTML, CSS rồi thì em có biết cấu trúc của 1 trang HTML gồm những gì và ý nghĩa như thế nào không?

- Cấu trúc của 1 trang html sẽ có 3 phần

* phần 1: DOCTYPE : sẽ khai báo chuẩn của HTML hay là XTML
* phần 2: Thẻ HEAD : sẽ khai báo ban đầu thường sẽ khai báo về thẻ META, TITLE, CSS, JAVASCRIPT
* phần 3: Thẻ BODY: phần này sẽ là nơi chứa nội dung của trang web, nơi hiển thị nội dung

### Câu 2: So sánh thuộc tính Class và ID trong HTML?

- Giống: Dùng để đặt tên và phân loại các phần tử, mục đích là để tiện cho việc quản lý và định dạng xử lí các phần tử sau này.
- ID: là duy nhất thường sẽ sử dụng trong form đê xử lý dữ liệu input của người dùng hoặc làm hiệu ứng cho thẻ
- Class: cũng tương tự như ID nhưng mình có thể đặt nhiều class giống nhau, đặc điểm là các class này sẽ có những định dạng css giống nhau.

### Câu 3: Trong CSS có một định nghĩa là Selector, em có nghe qua chưa?

- CSS selector thì nó giống như là một con trỏ trong css để chỉ định ra những thẻ mình muốn định dạng hoặc là tạo kiểu trong HTML.
- Có một số loại Selector cơ bản như sau:

* Simple selector: id, class, name
* Combinator selector: div > p {}, div p{}
* Pseudo-class selector: a:link , a:hover, a:active, a:first-child(), a:last-child()
* Pseudo-element selecttor: p::first-letter, p::first-line, p:before , p::after
* Atribute selector: a[target], a[target="_blank"] , [class^="top"]

### Câu 4: Một khái niệm quan trọng trong lập trình frontend là Box Model. Hãy giới thiệu về nó?

- Mỗi phần tử trong trang web đều có một khối hình chữ nhật riêng. Box Model là khoảng không gian phần tử đó chiếm trong trang web.
- Box Model bao gồm 4 thành phần chính:

* Content: là nội dung của phần tử
* Border: là đường viền của hình chữ nhật
* Padding: là khoảng đệm, là khoảng cách từ content tới border.
* Margin: là cái lề được tính từ border của phần tử này đến border của phần tử khác

### Câu 5: Display Block , Display Inline, Display Inline-Block là gì? Khác nhau như thế nào?

- Display Block: các item sẽ chiếm toàn bộ chiều rộng nếu chúng không được set chiều rộng (vd thẻ div). Đặc điểm là có thể set width, height, padding, margin đầy đủ 4 hướng
- Display Inline: các item cùng nằm trên cùng 1 dòng (vd như thẻ span), nếu độ dài quá dài thì nó sẽ xuống 1 dòng mới, đặc điểm là chúng không thể setWidth cũng như setHeight cho nó. Chỉ có thể điều chỉnh margin, padding Left Right ( Top và Bottom thì không thể chỉnh ).
- Display Inline-Block: sẽ được sắp xếp giống display: inline, nghĩa là các items sẽ được xép cùng nhau trên một dòng. Tuy nhiên các items này sẽ có thuộc tính của display:block đó là set width, height, margin, padding theo cả 4 hướng.

# C. JAVASCRIPT

### Câu 1. Javascript là gì? JS chạy được ở đâu, Fontend hay Backend?

- Javascript là một ngôn ngữ lập trình phổ biến nhất trên thế giới. Nó là một trong số 3 ngôn ngữ chính của lập trình web.

* HTML: Giúp bạn thêm nội dung cho trang web
* CSS: Định dạng thiết kế, bố cục , phong cách, canh lề của trang web.
* Javascript: Cải thiện cách họa động của trang web.

- Javascript được sử dụng trên nền tảng phát triển web. Nó vừa là giao diện người dùng vừa là backend

### Câu 1.b: Frontend là gì? Backend là gì? Fullstack là gì?

- Frontend là phần hiển thị của một trang web bao gồm cả những tương tác của người dùng, các hiệu ứng, màu sắc, ...
- Backend là nơi hỗ trợ hoạt động của website hoặc ứng dụng mà người dùng không thể nhìn thấy được. Nó chứa database, các api, server , ...
- Fullstack đơn giản là công việc bao gồm cả Frontend và Backend

### Câu 2. Các kiểu dữ liệu trong Javascript?

- String, Number, Boolean, Object, Undefined, Null.

### Câu 3: Khái niệm Hoisting trong JS?

- Hoisting là cơ chế mà trình thông dịch di chuyển tất cả các biến , hàm được khai báo lên đầu mã nguồn. Bất kể phạm vi của chúng là toàn cục hay cục bộ, chúng đều được trình thông dịch đưa lên đầu trong phạm vi của chúng.
- Nói đơn giản, Hoisting chính là việc chúng ta có thể sử dụng biến rồi khai báo nó sau.

* Giá trị của biến khi khai báo var là undefined
* Giá trị let và const vẫn được hoist nhưng nó không có giá trị nên sẽ báo lỗi Reference Error.

### Câu 4: Trong JS so sánh == và === khác nhau như thế nào?

- So sánh == được gọi là toán tử so sánh trừu tượng
- So sánh === được gọi là so sánh cân bằng nghiêm ngặt

- Toán tử so sánh trừu tượng sẽ cố gắng ép kiểu các toán hạng về dạng chung nhất sau đó mới so sánh
- Toán tử so sánh nghiêm ngặt thì sẽ không ép kiểu các toán hạng đó mà so sánh luôn.

### Câu 5. Một số phương thức xử lý mảng trong javascript?

- Concat(): nối mảng
- Filter(): Trả về tất cả các phần tử thỏa mãn điều kiện nào đó cho trước
- Find(): Tìm phần tử trong mảng dựa vào dữ liệu cho trước( 1 phần tử đầu tiên )
- ForEach(): gọi một hàm cho mỗi phần tử trong mảng
- Includes(): Tìm kiếm một phần tử có tồn tại trong mảng hay không ( true/false )
- IndexOf(): trả về chỉ mục đầu tiên của một phần tử trong mảng nếu tìm thấy, nếu không có thì trả về -1
- Join(): kết nối tất cả các phần tử trong một mảng thành một chuỗi và ngăn cách chúng bằng separator( mặc định là dấu phẩy)
- Map(): tạo một mảng mới với các kết quả của việc gọi một hàm đã cho trên mỗi phần tử của mảng này
- Pop(): Xóa phần tử ở cuối mảng và cho ra phần tử đã xóa
- Shift(): Xóa và lấy phần tử đầu mảng ra
- UnShift(): Thêm 1 hoặc nhiều phần tử và đầu mảng cho ra độ dài mới của mảng
- Push(): Thêm phần tử vào cuối mảng

### Câu 6: Sự khác nhau giữa forEach và Map?

- ForEach sẽ không trả về giá trị nào, forEach dùng hàm callback và thay đổi giá trị mảng ban đầu
- Map có trả về giá trị, map không thay đổi mảng ban đầu mà trả về một mảng mới có cùng số lượng phần tử của mảng cũ

### Câu 7: Những tính năng mới trong ES6 là gì?

- Những tính năng nổi bật trong ES6 đó là:

* let, const : Trước đây chỉ có var, từ ES6 có thêm let và const như 2 cách khai báo biến mới, hỗ trợ tầm vực theo khối (block scope) và không được hoisting
* Arrow function: Là một kiểu cú pháp rút gọn cho khai báo hàm trong Javascript
* Template string: Cúng giống như là string literals nhưng cho phép đính kèm biểu thức. Nó cũng cho phép khai báo chuỗi trên nhiều dòng. Cách dùng là sử dụng ký tự backtick ``(dấu huyền)
* Object literals: Cũng là khai báo một object như thường lệ, nhưng cho phép khai báo tắt thuộc tính của object với biến cùng tên và khai báo phương thức cho object.
* Destructuring (phân rã): Giúp ta tách biến từ thuộc tính của đối tượng hay phần tử trong các đối tượng có thể duyệt với for như là mảng hoặc chuỗi.
```
vd: var array=['java', 'c', 'ruby']
var [a, ,c]=array
=> console.log(a, c)=> java, ruby
```
* Rest: (Phần còn lại) là phần bổ sung của phân rã biến mảng. Rest được dùng khi khai báo hàm có thể nhận nhiều tham số.
```
vd: var array=['java', 'C', 'ruby']
var [a,...rest]=array
=> console.log(a)=> java
=> console.log(rest)=> C Ruby
```
* Spread: (Rải) là thao tác ngược lại với Rest, giúp ta kết hợp một mảng đã có sẵn thành một mảng mới. Spread rất hữu ích để thay thế các thao tác trên mảng như concat().
* Default value: Cho phép mình thiết lập giá trị mặc định cho tham số khi nó không được truyền giá trị hoặc có giá trị undefined. Thường dùng trong khi truyền giá trị vào hàm.
* Class: với ES5 chúng ta sử dụng function để tạo lớp và thêm các phương thức vào lớp bằng cách mở rộng prototype. Thì với ES6 chúng ta có cú pháp mới giúp tạo lớp trực tiếp và dễ dàng hơn. Có thể kế thừa từ lớp khác bằng từ khóa extends.
* Promises: Sinh ra để giúp chúng ta sử lý các tác vụ bất đồng bộ.

### Câu 8: Nói kỹ hơn về Promise?

- Promise sinh ra để giúp chúng ta sử lý các tác vụ bất đồng bộ
- Trước khi có promise ta thường sử dụng callback và callback xảy ra một vấn đề đó là callback hell, nó sẽ bị sâu vào gây khó nhìn, code dễ bị rối rắm, khó hiểu.
  ==> Promise được sịnh ra để khắc phục tình trạng callback hell
- Để tạo ra một Promise ta sử dụng từ khóa new với thằng Promise và trong constructor của nó ta truyền vào một executor function. Và trong executor func này sẽ nhận được hai tham số dưới dạng hàm.

  - Resolve: được gọi khi thao tác logic thành công
  - Reject : được gọi khi thao tác thất bại

```
var promise = new Promise(
    function(resolvem reject){
        resolve([data]);
        reject();
    }
)

promise
    .then(function(){
        return data
    })
    .then(function(data){
        console.log(data)
    })
    .catch(function(error){
        console.log(error)
    })
    .finally(function(){
        console.log("successfully!")
    })
```
- Khi chúng ta sử dụng Promise, chúng ta sẽ sử dụng 2 phương thức đó là (.then) và (.catch). Cả 2 phương thức này đều nhận callback 
    + sẽ được thực thi vào thằng then khi promise được resolve 
    + sẽ thực thi vào catch khi promise bị reject

- Promise có 3 trạng thái: 
    + Pending   : đang chờ thành công hay thất bại(rò rĩ bộ nhớ nếu nó chờ mãi)
    + Fulfilled : thành công (resolve được gọi)
    + Reject    : thất bại ( reject được gọi)


### Câu 8: So sánh giữa var, let và const ?

- var có phạm vi là function scope hoặc global scope, nó có thể gán lại và khai báo lại.
- let có phạm vi là block scope, có thể gán lại nhưng không thể khai báo lại
- const phạm vi là block scope, không thể gán lại cũng như không thể khai báo lại

### Câu 9: So sánh Function và ArrowFunction

- Arrow Func sử dụng ký hiệu là mũi tên, arrow function thường sẽ ngắn gọn hơn func bình thường
- Với hàm số có 1 tham số thì Arrow Func có thể bỏ qua dấu ngoặc đơn
- Arrow Func có thể bỏ qua từ khóa return
- Đối với Arrow func chúng ta không thể sử dụng hàm constructor, không có thuộc tính prototype, không được hoist ( tức là không thể dùng hàm trước khi khai báo )

### Câu 10: Khái niệm callback? Tại sao lại dùng callback ? Dùng trong những trường hợp nào khi code ?

- Callback là một hàm được truyền vào hàm khác dưới dạng đối số.
- Dùng trong trường hợp một hành động bất đồng bộ, một hành động nó chưa hoàn thành xong ngay lúc nó chạy thì ta truyền callback vào để chạy ngay sau khi có kết quả
- Dùng khi tạo một event hay gì đó thì ta đưa một callback function vào để khi người dùng bấm vào một cái nút hoặc hover chuột thì nó sẽ gọi cái hàm đó

### Câu 11: Khái niệm Closures ? Dùng Closures để làm gì ?

- Là một hàm có thể ghi nhớ nơi mà nó được tạo và truy cập được biến ở bên ngoài phạm vi của nó.

### Câu 12: Nút GoToTop code như thế nào bằng js ?

- Cách 1: window.scrollTo({top:0, behavior:'smooth})
- Cách 2: const element = document.getElementById('#id')
            element.scrollIntoView({behavior:'smooth', block:'start', inline:'nearest'})

### Câu 13: Dùng JS thì làm sao để check khi nào người ta điền form thì mới cho submit form?

- Truyền callback vào hàm onSubmit , sau đó viết hàm preventDefault, dùng JS lấy các thông tin họ đã điền và check xem đúng hay không. Nếu ok thì mới submit form.

### Câu 15. Thuật toán sắp xếp nào nhanh nhất?

-> Quicksort n.log(n)

### Câu 16. Cho một mảng đã sắp xếp -> Tìm một phần tử trong mảng thì dùng thuật toán gì?

-> Binary search -> độ phức tạp là log(n)

### Câu 17. Cho một mảng bình thường -> Tìm phần tử lớn thứ 2 trong mảng

- Cách 1: Lưu 2 biến chứa phần tử lớn thứ nhất và thứ 2, mối lần duyệt thì ta sắp xếp và so sánh 2 cái biến đó.
- Cách 2: Duyệt lần 1 tìm phần tử lớn nhất sau đó remove nó ra, duyệt lần 2 thì ta sẽ có đc phần tử lớn thứ 2
- Cách 3: Sắp xếp các phần tử và lấy phần tử lớn thứ 2 ( câu này thích hơn cho tìm phần tử lớn thứ n trong mảng)

### Câu 18: Phân bệt Server-side và Client-side

- Server-side: Phần lớn logic sẽ được xử lý ở server.
    + Khi người dùng vào một trang web, trình duyệt sẽ gởi GET request tới web server.
    + Web server sẽ nhận request, đọc dữ liệu từ database.
    + Web server sẽ render HTML, trả về cho browser để hiển thị cho người dùng.
    ==> Logic từ đơn giản đến phức tạp, logic để routing, để render đều nằm ở server

    - Ưu điểm: 
        + Thân thiện với SEO vì BOT của Google hay Bing vào website sẽ thấy toàn bộ dữ liệu dưới dạng HTML. 
        + Tương thích trên rất nhiều trình duyệt khác nhau vì nó đã ra đời rất là lâu rồi. 
        + Thời gian load lần đầu tiên rất nhanh.
    - Nhược điểm: 
        + Khi nhận được request về cơ bản thì HTML đã được hiện lên nhưng chưa thể tương tác gì JS sẽ tải chậm hơn nên cần phải tải xong cả JS mới có thể tương tác được.
        + Khi chuyển trang thì web sẽ load lại toàn bộ từ đầu gây ảnh hưởng đến trải nghiệm người dùng.
        + Nếu lượng request lên server nhiều thì dễ gây chậm và quá tải
        + Tốn băng thông vì server phải gởi lại nhiều dữ liệu trùng và thừa.

- Client-side: Là việc render HTML, CSS được thực hiện ở Client (tức là Javascript ở trình duyệt)
    + Những logic đơn giản , logic routing, render nằm ở Client-side
    + Những logic phức tạp như thanh toán, phân quyền hoặc cần xử lý nhiều thì vẫn nằm ở Server-side

    - Ưu điểm:
        + Giải quyết mặt hạn chế của Server-side
        + Khi chuyển trang khá nhanh , cải thiện trải nghiệm người dùng đáng kể so với server-side
    - Nhược điểm:
        + Load lần đầu khá chậm vì để render được HTML , client phải tải JS về sau đó chạy JS để DOM và gọi API
        + Không tốt cho SEO bằng server-side vì nội dung được sinh ra ở client nên các con Bot không dễ dàng tìm kiếm và đọc được dữ liệu.

### Câu 19: Bất đồng bộ trong Javascript

- Javascript là ngôn ngữ lập trình bất đồng bộ và chỉ chạy trên một luồng. Sự bất đồng bộ trong javascript xuất hiện khi nó thao tác với các WebAPI (ajax, setTimeout(), … ). Khi một câu lệnh thao tác với WebAPI, nó sẽ mất một khoảng thời gian để chờ các dữ liệu trả về từ WebAPI, do đó ở trong luồng chính của javascript, nó sẽ ở trong trạng thái chờ. Tuy nhiên chương trình sẽ không bỏ trống khoảng thời gian chờ đó, chương trình sẽ tiếp tục thực hiện các câu lệnh tiếp theo. Đó là lý do Javascript là ngôn ngữ bất đồng bộ

### Câu 20: Promise và Async-Await

- Promise tức là một action mà cần thời gian để lấy data về
- Async: báo cho js là tôi muốn viết theo kiểu async - await , hay cách khác là function này là kiểu promise
- Await: tức là phải chờ cho nó lấy dữ liệu, phải có async ở đầu hàm

### Câu 21. Bind() method?

- Phương thức bind() cho phép ràng buộc this cho một phương thức (function)
- Bind() sẽ trả về một hàm mới, có thể nhận các đối số nư hàm ban đầu.
- Khi dùng phương thức Bind() thì tham số truyền vào () sẽ là đối tượng cho this, nó sẽ tạo ra một hàm mới và đối tượng là tham số này.
- Có thể mượn hàm
VD: const student = {name:'Quang', age:18}
const teacher = {
    name:'Dung, 
    age:20 ,
    getName(){
        return `${this.name} ${this.age}`
    }
}

const getStudentName = teacher.getName.bind(student) ==> Quang 18
const getTeacherName = teacher.getName.bind(teacher) ==> Dung 20

===> Nó sẽ trỏ đến đối tượng nằm trong bind() là student hay là teacher để lấy data tương ứng.

### Câu 22. Call() method?

- Call() là phương thức trong prototype của function constructor, phương thức này được dùng để gọi hàm và cũng có thể bind this cho hàm.
- Bind() và Call() khác nhau
    + Bind() là chỉ bind()
    + Còn Call() là bind()  xong rồi call() chạy hàm luôn.
- Call() có thể mượn hàm

VD: const student = {name:'Quang', age:18}
const teacher = {
    name:'Dung, 
    age:20 ,
    getName(){
        return `${this.name} ${this.age}`
    }
}

teacher.getName() ==> Dung 20
teacher.getName.call(student) ==> Quang 18
teacher.getName.call(teacher) ==> Dung 20


- Call() có tính kế thừa.

VD:  
function Animal(name, weight){
    this.name =name
    this.weight = weight
}

function Chicken(name, weight, legs){
    Animal.call(this, name, weight)
    this.legs = legs
}

const data = new Chicken('Quang', 60, 2)
console.log(data) ==> Chicken {name:'Quang', weight: 60, legs:2}

### Câu 23. Apply() method?

- Apply(): Phương thức này cho phép gọi 1 hàm với 1 this (bind) và truyền đối số cho hàm gốc dưới dạng mảng.
- Apply() có thể mượn hàm.

VD const teacher = {firstName: 'Minh', lastName:'Thu'}
function greet(greeting, message){
    return `${greeting} ${this.firstName} ${this.lastName} ${message}`
}

let result = greet.apply(teacher,['Hi', 'Xin chao'])
==> console.log(result)  ==> Hi Minh Thu Xin chao

- Tính kế thừa giống call() chỉ khác 1 thứ

VD  function Chicken(){
        Animal.call(this, argument)
        this.legs = legs
    }
hoặc có thể viết như sau:
    function Chicken(name, weight, legs){
        Animal.call(this, [name, weight])
        this.legs = legs
    }


### Câu 24. So sánh bind(), call(), apply()?

- Giống:
    + Là các method được kế thừa từ function.prototype
- Khác nhau: Các đối số và cách hoạt động.
    + Bind(): 
        - Trả ra hàm mới với `this` tham chiếu tới `thisArg`
        - Không thực hiện gọi hàm
        -Nếu được bind() kèm `arg1, arg2, ...` thì các đối số này sẽ được ưu tiên hơn.
        
        const newFn = fn.bind(thisArg, arg1, arg2, ...)
        newFn(arg1, arg2, ...)

    + Call():
        - Thực hiện bind `this` với `thisArg` và thực hiện gọi hàm
        - Nhận các đối số cho hàm gốc từ `arg1, arg2, ...`

        fn.call(thisArg, arg1, arg2, ...)

    + Apply():
        - Thực hiện bind `this` với `thisArg` và thực hiện gọi hàm
        - Nhận các đối số cho hàm gốc bằng đối số thứ 2 dưới dạng mảng `[arg1, arg2, ...]`

        fn.call(thisArg,[arg1, arg2, ...])




### Câu 25: IIFE - Immediately Invoked Function Expresstion ?

- IIFE là biểu thức sẽ tạo ra 1 hàm và hàm đó sẽ được gọi ngay lập tức.

```
(function(message){
    console.log(message)
})("hello)
```

- Dùng đấu ; trước IIFE để tránh các lỗi gọi hàm của dòng code bên trên, để khẳng định rằng 2 dòng này là không liên quan đến nhau
- IIFE là hàm `private` => chúng không thể gọi lại hàm này ở ngoài hàm, nhưng có thể gọi lại trong chính hàm của nó (đệ quy)
- Dùng IIFE khi ta khống muốn chúng ảnh hưởng đến các biến global
- Các giá trị trả về của IIFE nằm trong return nên các biến bí mật t ko đưa vào đó để tạo tính private cho chúng.


# D. React JS

### Câu 1: SPA - MPA là gì? Sự khác nhau?

- SPA: Single Page App
    + Được cho là cách tiếp cận hiện đại hơn
    + Không yêu cầu tải lại trang trong quá trình sử dụng
    + Google, Facebook, Twitter

- MPA: Multi Page App
    + Là cách tiếp cận cổ điển hơn
    + Tải lại trang trong quá trình sử dụng

- Tốc độ:
    + SPA nhanh hơn khi sử dụng, phần lớn tài nguyên được tải ngay lần đầu, trang chỉ tải thêm dữ liệu mới khi cần
    + MPA chậm hơn khi sử dụng, luôn tải lại toàn bộ trang khi tải lại hoặc chuyển hướng.

- Bóc tách:
    + SPA có phần Front-end riêng biệt
    + MPA Frontend và Backend phụ thuộc nhau nhiều hơn, được đặt trong cùng một dự án.

- SEO:
    + SPA không thân thiện với SEO như MPA
    + SPA trải nghiệm tren thiết bị di động tốt hơn.

- Quá trình phát triển:
    + SPA dễ dàng tái sử dụng code (component)
    + SPA bóc tách Frontend - Backend => chia team phát triển song song, phát triển thêm mobile app dễ dàng.

- Phụ thuộc Javascript
    + SPA phụ thuộc hoàn toàn vào javascript
    + MPA có thể không cần Javascript

- Chọn SPA hay MPA
    + Không có gì là hoàn hảo trong mọi trường hợp. Nhưng hiện tại SPA vẫn đang là lựa chọn tốt hơn so với MPA


### Câu 2: Tại sao phải sử dụng React - DOM

- React DOM làm một thư viện, là cầu nối giữa REACT và DOM
- Để ta có thể render React Element ra trình duyệt.

### Câu 3: Sự khác nhau giữa Functional Component (stateless) và Class Component (stateful) trong ReactJS?

- Functional component (stateless) là hàm không có local state và cũng không có lifecycle method , vì thế cũng không có componentDidMount.
- Class component (stateful): là hàm có state, có lifecycle method

==> Chúng ta thường sẽ dùng class component khi chúng ta cần có state
==> Chúng ta sẽ dùng Functional component khi chung ta không cần có state

===> Chọn Functional component vì nó gọn hơn, dễ test hơn vì khi viết một hàm thì cái hàm nó sẽ dễ đọc hơn với input là props, output là render. Thay vì việc phải viết một cái class component có extend , có hàm render, rồi đủ thứ hàm khác nữa.


### Câu 4. Trong component khi muốn lấy dữ liệu từ server để hiển thị ra thì cái hàm lấy dữ liệu ta sẽ viết trong function nào?

- ComponentDidMount
- ComponentDidMount được gọi sau khi được render

### Câu 5: React có gì hay mà người ta dùng nhiều vậy ?

- React có tách thành các components nên cách viết code nó sẽ tiện hơn và tính tái sử dụng rất cao.

### Câu 6: Sự khác nhau giữa Props và State?

- Props là viết tắt của Property là đối số của component và không thể thay đổi được giá trị của Props
- State là giá trị riêng của Component, và ta có thể thay đổi được giá trị của state, khi state thay đổi thì component sẽ được re-Render.


## REACT HOOKS

### Câu 7. kể tên một số Hook trong ReactHook?

- useState, useEffect, useReducer, useMemo, useCallback, useRef, ...

### Câu 8: useState trong React Hooks?

- useState dùng khi muốn dữ liệu thay đổi thì giao diện tự động cập nhật (Re-render theo dữ liệu)

### Câu 9: Two-way binding?

- Gõ bên ngoài thì bên trong thay đổi , bên trong thay đổi thì bên ngoài thay đổi.

```
vd: ô input ta gõ dữ liệu vào thì nó hiện lên

const [name ,setName] = useState('')
<input value={name} onChange={e=>setname(e.target.value)}/>

```

### Câu 10: Mounted & UnMounted ?

- Mounted: là thời điểm đưa component vào sử dụng
- UnMounted: là thời điểm lấy component ra không sử dụng nữa

### Câu 11: useEffect trong React Hooks?

- useEffect dùng khi ta muốn thực hiện các side effects (khi có 1 tác động xảy ra dẫn tới dữ liệu của chương trình bị thay đổi)
- Luôn được gọi khi component mounted

- Cách sử dụng useEffect():

- useEffect(callback):
    + Gọi callback mỗi khi re-render
    + Gọi callback sau khi component thêm element vào Dom ( tức là return() được chạy xong thì chạy useEffect)
- useEffect(callback,[]):
    + Chỉ gọi callback một lần sau khi component được mounted
- useEffect(callback, [deps]):
    + Callback sẽ được gọi sau khi deps thay đổi

- Áp dụng:
    + update DOM
    + Call API
    + Listen DOM Event(scroll, resize)
    + Cleanup (remove listener/ unsubscribe, clear timer)

- Lưu ý: 
    + Clean up function luôn được gọi trước khi callback được gọi (trừ lần mounted)
    + Trước khi callback lần tiếp theo thì clean up sẽ dọn dẹp lần trước đó
    + Từ lần callback thứ 2 thì clean up mới được chạy và chạy trước callback

```
vd:
    useEffect(()=>{
        code here...
        return()=>{
            dọn dẹp
        }
    }, [deps])
```

### Câu 12: useLayoutEffect trong React Hooks?

- useEffect và useLayoutEffect rất giống nhau về mặt ý nghĩa, cú pháp. Nhưng khác nhau thứ tự thực hiện.
- Cả 2 hooks này sinh ra để giúp chúng ta có chỗ để xử lý các side effect

- useEffect
    1. Cập nhật lại state
    2. Cập nhật DOM (mutated)
    3. Render lại UI
    4. Gọi clean up nếu deps thay đổi
    5. Gọi useEffect callback

- useLayoutEffect
    1. Cập nhật lại state
    2. Cập nhật DOM
    3. Gọi clean up nếu deps thay đổi
    4. Gọi useLayoutEffect callback
    5. Render lại UI

### Câu 13: useRef trong react hooks?

- Dùng để lưu các giá trị qua 1 tham chiếu bên ngoài function component (ref : reference (tham chiếu))
- useRef sẽ luôn trả về một Object chó property là current


### Câu 14: useCallback() trong React Hooks?

- Giúp ta trả lại tham chiếu trước đó thay vì trả ra 1 hàm mới
- Cú pháp giống useEffect --> useCallback(callback,[deps])
- useCallback chỉ có tác dụng khi có memo mà thôi

### Câu 15: `useMemo()` trong React Hooks?

- Khác nhau giữa `useMemo()` và `memo()`
    + `useMemo()`: Được viết trong phần thân của func component, chức năng tránh thực hiện lại một logic nào đó không cần thiết
    + `memo()`: Ôm thằng React component chúc năng tránh component bị re-render trong những tình huống không cần thiết

### Câu 16: useReducer() trong React Hooks?

- `useReducer` cung cấp cho ta thêm 1 sự lựa chọn để sử dụng `state` cho function component
- Trong bất cứ bài toán nào dùng `state` giải quyết được thì dùng `useReducer` cũng có thể giải quyết được

- `useState`: dùng khi có các `state` đơn giản như số, chuỗi, boolean, array, object đơn giản
- `useReducer` dùng khi có `state` phức tạp như array, object lồng nhau phức tạp. Các state liên kết với nhau, ảnh hưởng trực tiếp lên nhau thì ta nên dùng `useReducer`.

- Cách triển khai
    + useState()
        1. Init State
        2. Actions

    + useReducer()
        1. Init state
        2. Actions
        3. Reducer
        4. Dispatch

### Câu 17: `useContext()` trong React Hooks?

- useContext() giúp đon giản hóa việc truyền dữ liệu từ các component cha sang các component con mà không phải sử dụng đến props
- Cách dùng:
    1. Create Context (tạo context)
    2. Provider (cung cấp)
    3. Consumer (nhận dữ liệu)

### Câu 18: `useImperativeHandle()` trong React Hooks?

- Giúp ta có thể tùy chỉnh được ref của func component

### Câu 19: React Router V6?

- React Router tạo ra cơ chế định tuyến nội bộ.



## REACT HOC (Higher Order Component)

### Câu 1. React.memo()?

- Giúp chúng ta xử lí 1 component để tránh bị re-render trong những tình huống không cần thiết.
vd: khi ta có 2 tham số và 1 tham số truyền xuống component con và 1 tham số khác được sử dụng ở component cha. Khi tham số ở component con thay đổi thì render lại, còn tham số chỉ được dùng ở component cha thì component con không cần render lại.






# E. API

### 1. Restful API là gì?

- REST viết tắt của REpresentational State Transfer (chuyển trạng thái biểu diễn)
- API [Application Programing Interface]: giao diện lập trình ứng dụng hay còn gọi là cổng giao tiếp giữa các phần mềm. 
- Restful API (RestAPI): là một giao diện lập trình ứng dụng (API) mà tuân thủ các ràng buộc và quy ước kiến trúc REST được sử dụng trong việc giao tiếp giữa client và server

- Backend -> API(URL) -> Fetch -> JSON/XML -> JSON.parse -> Javascript types -> Render ra gao diện

### Câu 2. FetchAPI trong React?

```
function App() {
	const [data, setData] = useState([]);

	useEffect(() => {
		// API_ENDPOINT là bất kỳ đường dẫn API nào trả về dạng JSON
		fetch("API_ENDPOINT")
			.then(response => {
				// Kiểm tra trạng thái phản hồi
				if(!response.ok) {
					throw new Error(response);
				}
				
				// Phản hồi không lỗi, trả về JSON cho then tiếp theo lấy dữ liệu
				return response.json();
			})
			.then(data => {
				// Lấy dữ liệu và setState cho data
				setData(data);
			})
			.catch(err => alert("Có lỗi"))
			.finally(() => {
				console.log("End")
			})
	}, [])
	
	return <div>Demo</demo>
}
```


# F. REDUX - REDUX SAGA