# Ứng dụng đặt đồ uống

![image](https://github.com/user-attachments/assets/f0efaca0-bd55-4829-ac50-1566451a4c3f)
![image](https://github.com/user-attachments/assets/65d9fcbb-b19e-4e25-973f-40a055f83a75)
![image](https://github.com/user-attachments/assets/4808e67c-ca48-4959-9804-98360ef6471c)


## Thành viên

| MSSV | Họ và tên |
| -------- | ------- |
| 2001210660 | Huỳnh Thế Vinh |
| 2001210412 | Trần Thị Ngọc Nhi |
| 2001215976 | Phan Thị Thanh Nga |

## Mã nguồn
- Backend / API: [Source code backend](https://github.com/coffee-app-udtm/coffee-ecommerce-server)
- Website: [Source code website](https://github.com/coffee-app-udtm/coffee-ecommerce-client)
- Winform Library: [Source winform lib](https://github.com/coffee-app-udtm/coffee-ecommerce-library)
- Winform admin: [Source winform admin](https://github.com/coffee-app-udtm/coffee-ecommerce-admin-form)
- Winform cửa hàng: [Source winform store](https://github.com/coffee-app-udtm/coffee-ecommerce-store-form)
  
## Công nghệ
- Backend: Sử dụng Nodejs, Expressjs để làm server phía backend cung cấp api

- Frontend: Sử dụng Nextjs, NextUI, Tailwindcss, Firebase, SWR, Zustand

- Database: Sử dụng Mysql

- Desktop: Winform C#, Visual Studio 2022

- Xác thực: Sử dụng dịch vụ Firebase để xác thực đăng ký, đăng nhập ( email, google ) cho cả website và ứng dụng di động

- Lưu trữ: Sử dụng Firebase Storage để lưu các file hình ảnh

- Ứng dụng di động: Sử dụng Java Android và IDE Android Studio,

- Thanh toán online: Sử dụng các tài khoản test của momo, vnpay

- Các công cụ hỗ trợ:
  - Dbdiagram thiết kế database
  - Postman dùng cho test api
  - Notion tạo tài liệu hướng dẫn sử dụng cho api
    
![image](https://github.com/user-attachments/assets/abb735c2-b9cb-4e14-8f96-5bd8292b15e8)


## Mô tả chi tiết
### Website, Android 
1. Mua hàng trực tuyến:
   - Cho phép khách hàng duyệt qua danh mục sản phẩm, chọn sản phẩm và thêm vào giỏ hàng.
   - Hỗ trợ thanh toán trực tuyến qua nhiều hình thức thanh toán khác nhau.

2. Quản lý tài khoản khách hàng:
   - Đăng ký và đăng nhập tài khoản khách hàng.
   - Quản lý thông tin cá nhân
   - Xem lịch sử mua hàng và theo dõi trạng thái đơn hàng.
   
### Winform C#
1. Bán hàng tại quán:
   - Giao diện sử dụng bán hàng trực tiếp tại quán.
   - Quản lý đơn hàng tại quán, bao gồm các tùy chọn tùy chỉnh đơn hàng như thêm hoặc bỏ các thành phần món ăn.
   - Hỗ trợ thanh toán trực tiếp, in hóa đơn.

2. Quản lý doanh thu tại các quán:
   - Báo cáo doanh thu theo ngày, tuần, tháng, hoặc theo thời gian tùy chỉnh.

3. Admin quản lý:
   - Quản lý doanh thu các chi nhánh
   - Quản lý khách hàng
   - Quản lý tài khoản
   - Quản lý sản phẩm
   - Quản lý danh mục, topping, size

## Phân công
### Winform C#
| STT | Nghiệp vụ | Phân công |
| -------- | ------- | -------- |
| 1 |  Đăng nhập admin / cửa hàng    | Nga 
| 2 |  Form dashboard | Nga
| 3 |  Form quản lý size | Nga
| 4 |  Form quản lý topping | Nga
| 5 |  Form quản lý sản phẩm | Nhi
| 6 |  Form quản lý danh mục | Nhi
| 7 |  Form quản lý tài khoản | Nhi
| 8 |  Form doanh thu cửa hàng - tổng | Nhi
| 9 |  Form bán hàng | Vinh
| 10 |  Form quản lý đơn hàng | Vinh
| 11 |  Form khách hàng | Vinh

### Android
| STT | Nghiệp vụ | Phân công |
| -------- | ------- | -------- |
| 1 |  Activity đăng ký    | Nga 
| 2 |  Activity đăng nhập | Nga
| 3 |  Activity danh sách các cửa hàng | Nga
| 4 |  Activity profile | Nhi
| 5 |  Activity giỏ hàng | Nhi
| 6 |  Activity chi tiết sản phẩm + thêm giỏ hàng | Nhi
| 7 |  Activity thanh toán | Vinh
| 8 |  Activity đơn hàng | Vinh



### Website + API
| STT | Nghiệp vụ | Phân công |
| -------- | ------- | -------- |
| 1 |  Viết API   | Vinh 
| 2 |  Triển khai website | Vinh
| 12 |  Chatbot API | Nga + Nhi + Vinh


## Triển khai chức năng

### Winform

-   Dashboard
  
![image](https://github.com/user-attachments/assets/45b499ab-2b4b-4808-8713-76c1c684a922)

-   Doanh thu
  
![image](https://github.com/user-attachments/assets/aed0ea5a-fbb1-4705-896d-54da61a221ab)

-   Khách hàng
  
![image](https://github.com/user-attachments/assets/944a922e-2b94-459f-b06b-d9322210044d)


-   Tài khoản cửa hàng
  
![image](https://github.com/user-attachments/assets/b5cccd37-fcb4-4004-9b1b-94621af36ce8)


-   Sản phẩm
  
![image](https://github.com/user-attachments/assets/10ca8729-e6db-4536-88bd-a6687504f78b)
![image](https://github.com/user-attachments/assets/36510bf6-2330-4b41-9a94-40d4948a6065)
![image](https://github.com/user-attachments/assets/b20ce5c1-7b75-4d8a-85ba-ab57f1e84401)

-   Danh mục
  
![image](https://github.com/user-attachments/assets/b605d698-0a76-4992-a23d-c1cb350a44d5)

-   Size
  
![image](https://github.com/user-attachments/assets/361bc1de-9f90-4f6b-8318-0477f2ff4813)


-   Topping
  
![image](https://github.com/user-attachments/assets/08900491-acdb-4c34-8ff3-ce66defc292c)

-   Bán hàng
  
![image](https://github.com/user-attachments/assets/4a0c6cce-bc19-4a04-85dd-4df5004ab50e)


-   Đơn hàng
  
![image](https://github.com/user-attachments/assets/52946b5c-43fa-4f7f-8827-9e63be1c1cc8)
![image](https://github.com/user-attachments/assets/e1ecba64-242d-4bc2-90be-f5a07371bca9)






### Website

-   Menu

![image](https://github.com/vinbuddy/coffee-ecommerce-client/assets/94288269/5845f424-b566-4415-af55-4b692ea2c70b)

-   Sản phẩm

![image](https://github.com/vinbuddy/coffee-ecommerce-client/assets/94288269/04f7606d-fdc5-4c66-91f2-8d71a55efe11)
![image](https://github.com/vinbuddy/coffee-ecommerce-client/assets/94288269/46049d36-4c1f-4a7f-bff1-4a20f4cf3e3b)

-   Giỏ hàng

![image](https://github.com/vinbuddy/coffee-ecommerce-client/assets/94288269/5fd018ed-0259-4d0c-a8ac-018f3ef3f571)

-   Thanh toán

![image](https://github.com/vinbuddy/coffee-ecommerce-client/assets/94288269/79f3acac-ba6a-482f-af4a-9ef1bc5e8949)

-   Trang cá nhân

![image](https://github.com/vinbuddy/coffee-ecommerce-client/assets/94288269/df76cbab-e987-46ab-b1a5-121f19ed3f97)

-   Đơn hàng

![image](https://github.com/vinbuddy/coffee-ecommerce-client/assets/94288269/6d308226-073c-4fde-9252-ffc615cb4d11)

![image](https://github.com/vinbuddy/coffee-ecommerce-client/assets/94288269/996ae6c1-21d9-40be-a1df-d3d21df95adf)


### Android
- Xác thực
<p align="left">
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/ec76506b-021d-491c-ba7e-14322b896421" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/1e1393db-c518-4858-b587-c305df6e34f0" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/56ac4d95-1533-4c95-a05f-ef5507fda225" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/d4b1ec46-5412-446b-9fcc-a0ce26190e56" width="200" /> 
</p>

- Sản phẩm
<p align="left">
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/1e3ac6b6-7ce7-4e35-a975-c5540f1378ab" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/2b9caa36-fc82-4ae8-98eb-fc989ba78270" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/8dd48bfa-36ec-4427-80f7-3294cba9a054" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/fe8018b7-e223-4d14-b4a1-8203adedcbef" width="200" />
</p>

- Chi tiết sản phẩm
<p align="left">
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/f9297c9b-d22d-4968-8ace-d3b263857c67" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/6e694f9d-7a7f-4361-88a6-e4f89b8c395a" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/c4126828-03bf-42aa-8f56-a09199491f00" width="200" />
</p>

- Giỏ hàng
<p align="left">
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/0f5821bd-a6cd-4481-90ae-7c5fb13c257d" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/bef37573-9669-46c3-bb60-c4a9434f4cd1" width="200" />
</p>

- Trang cá nhân
<p align="left">
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/00d9def4-3204-4008-b9b7-d56e871855a1" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/d8b2832f-4342-490c-9f51-7c018ba57ff2" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/b296a62c-98b0-4123-9d30-80997bb7a37e" width="200" />
</p>

- Đặt hàng
<p align="left">
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/8afd1b08-1836-41c6-8c3c-7ba9a0e98d0e" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/b3e0e072-9bcb-4409-b0fa-877520c7c36c" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/a1b5fc40-7a33-40be-a65a-b386a099f43c" width="200" />
</p>

- Thanh toán online
<p align="left">
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/70ab8a90-ed1f-49e1-8ab7-25ca02ee8dcf" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/d7ec44f1-9ef0-4678-aa51-9197d967e3c4" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/c1fde074-97b3-4f8a-b3df-6071579121ed" width="200" />
</p>

- Theo dõi đơn hàng
<p align="left">
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/ea279c83-a600-4cb4-89cc-d60be2353f1c)" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/637ccb09-7d0f-4ad7-afd4-de480f7d2c5b" width="200" />
</p>

- Lịch sử đơn hàng
<p align="left">
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/2259240f-6313-458a-b561-d2343f12ee28" width="200" /> &nbsp;
  <img src="https://github.com/vinbuddy/coffee-ecommerce-android/assets/94288269/ebe9f8a1-93bb-4072-a16f-734ebdd34d0e" width="200" />
</p>

