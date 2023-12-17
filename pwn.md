# Pwn

**A gift for pwners**<br />
>&nbsp;&nbsp;&nbsp;Ta sẽ phân tích xem file được cấp là file như thế nào.<br/>
![agfp](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/24399a1a-fc27-4f24-8c13-25029246fc55)<br/>
&nbsp;&nbsp;&nbsp;Ta thấy rằng đây là file ELF64, thế nên ta sẽ dùng ida bản 64-bit để đi sâu hơn vào file này. Sau khi đã vào được, ta sẽ dùng tổ hợp phím Shift + F12 để xem các chuỗi có trong
> file này. Và tình cờ rằng ta sẽ thấy được 3 phần của flag đưa rải rác khắp nơi trong file. Từng phần lần lượt là: ``KCSC{A_gift_`` + ``for_the_`` + ``pwners_0xdeadbeef}``<br/>
&nbsp;&nbsp;&nbsp;Ta sẽ thử submit với các phần flag đó và thành công.<br/>
&nbsp;&nbsp;&nbsp;Vậy flag sẽ là: ``KCSC{A_gift_for_the_pwners_0xdeadbeef}``<br/>
