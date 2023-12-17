# KCSC-Recruitment

**Real Warmup**<br />
Trước tiên, ta dùng die(Detect It Easy) để xác định thông tin file chall.exe.<br />
![rw1](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/b7268efe-69a3-4e23-af7d-a495768508dc)<br />
Ta thấy file này đang thực thi ở PE64 tức là 64bit, ta sẽ dùng ida(The Interactive Disassembler) bản 64-bit để phân tích file trên.<br />
![rw2](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/e7273641-b78b-4272-980a-1e36c7f46441)<br />
Ta sẽ dùng tổ hợp phím Shift + F12 để xem các chuỗi.<br />
![rw3](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/0cace6fd-9960-4ea3-9ba6-a2f3b12f5e03)<br />
Đây có thể sẽ là flag, ta double click vào chuỗi đó.<br />
![rw4](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/43a1cadb-aad7-455c-92c8-e7620c41e859)<br />
Tiếp đến ta sẽ dùng tổ hợp Ctrl + x, và F5. Ta sẽ nhận được mã giả hay pseudocode của file này.<br />
![rw5](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/ecf8be81-0084-42d4-9b86-56ceaf267808)<br />
Đoạn code này để kiểm tra xem chuỗi ta nhập vào có giống chuỗi đã cấp từ trước hay không, như vậy có thể chuỗi đó sẽ là flag của bài này, ta sẽ kiểm tra lại 1 lần nữa.<br />
![rw6](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/db0e18e2-5472-4749-b4dd-39c09da4b54f)<br />
Như vậy đã đúng là flag của bài, nhưng tiếp đến ta sẽ dùng [cyberchef](https://cyberchef.org/) hoặc là một số phần mềm khác tương đương.<br />
ở đây ta sẽ dùng recipe From BASE64 và let him cook.<br />
![rw7](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/72facd30-3098-4346-9045-a7f965f5d121)<br />
Ta thu được flag là: KCSC{Ch40`_M|_|n9`_D3N'_V01'_77\/_KCSC}.<br />

-------------------------------------
**hide and seek**<br />
Ở bài này, ta sẽ thử chạy file dropFile.exe và được như sau.<br />
![has1](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/132d7ce8-7fc1-4859-ba71-c78ca0774f4e)<br />
Ta thấy đường dẫn hiện ra, truy cập vào file theo đường dẫn đó sẽ dẫn ta đến 1 trang web như sau.<br />
![has2](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/fcbc9302-d6b8-4db3-af0e-da71fcd51dc8)<br />
Ta sẽ chọn VIEW FLAG, và nhận được kết quả là:<br />
![has3](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/66d76c56-ce23-4d45-a24a-cf1f937a5c54)<br />
flag sẽ là KCSC{~(^._.)=^._.^=(._.^)~}

------------------------------------
**Images**
![image1](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/6a2ac236-2d0f-4d8d-b3b6-f8e4d5350549)<br />
Khi xem ảnh thứ 3, thấy 75 theo ascii sẽ là chữ "K" trùng với format flag của giải ở vị trí số 0. Từ đó ta sẽ lọc các số cũng như là vị trí của nó. Tiếp đến ta sẽ sắp xếp lại vị trí của các chữ tương ứng với vị trí.<br />
![image2](https://github.com/ng0cph0ng/KCSC-Recruitment/assets/93986136/57f67c70-136d-47bd-a216-c3882b46eb01)<br />
Và ta sẽ thu được flag là: KCSC{Cam_on_vi_da_kien_nhan_nhin_het_dong_anh_nay`}
