# KCSC-Recruitment

Real Warmup
Trước tiên, ta dùng die(Detect It Easy) để xác định thông tin file chall.exe.
![rw1](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/b7268efe-69a3-4e23-af7d-a495768508dc)
Ta thấy file này đang thực thi ở PE64 tức là 64bit, ta sẽ dùng ida(The Interactive Disassembler) bản 64-bit để phân tích file trên.
![rw2](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/e7273641-b78b-4272-980a-1e36c7f46441)
Ta sẽ dùng tổ hợp phím Shift + F12 để xem các chuỗi.
![rw3](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/0cace6fd-9960-4ea3-9ba6-a2f3b12f5e03)
Đây có thể sẽ là flag, ta double click vào chuỗi đó.
![rw4](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/43a1cadb-aad7-455c-92c8-e7620c41e859)
Tiếp đến ta sẽ dùng tổ hợp Ctrl + x, và F5. Ta sẽ nhận được mã giả hay pseudocode của file này.
![rw5](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/ecf8be81-0084-42d4-9b86-56ceaf267808)
Đoạn code này để kiểm tra xem chuỗi ta nhập vào có giống chuỗi đã cấp từ trước hay không, như vậy có thể chuỗi đó sẽ là flag của bài này, ta sẽ kiểm tra lại 1 lần nữa.
![image](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/db0e18e2-5472-4749-b4dd-39c09da4b54f)
Như vậy đã đúng là flag của bài, nhưng tiếp đến ta sẽ dùng cyberchef(https://cyberchef.org/) hoặc là một só phần mềm tương đương.
