<h1>Amazon S3 - Upload Image</h1>

<h3>Hướng dẫn tạo tài khoản IAM trên AWS</h3>

<h5>Bước 1</h5> 

- Tạo tài khoản **Root User** trên AWS 
- Truy cập https://aws.amazon.com/console/
- Trên thanh tìm kiếm gõ: **IAM**
- Bấm vào User groups -> Create group
- Nhập tên
- Ở phần Attach permissions policies, trên thanh tìm kiếm gõ: **ADMINISTRATOR**
- Nhấp vào checkbox: AdministratorAccess
- Nhấp nút "Create group" màu xanh dương 

<h5>Bước 2</h5> 

- Truy cập https://aws.amazon.com/console/
- Trên thanh tìm kiếm gõ: **IAM**
- Bấm vào Users -> Add users
- Nhập user name, nhấp vào password(Custom password)
- Nhập password
- Bỏ nhấp ở phần Require password reset
- Next permissions
- Nhấp vào checkbox group mà ở B1 đã tạo ở phần Add user to group
- Next
- Next Review
- Create user

<h5>Bước 3</h5>

- Truy cập https://aws.amazon.com/console/
- Trên thanh tìm kiếm gõ: **IAM**
- Bấm vào Dashboard
- Bên phải màn hình phần AWS Account
- Nhấn đường link Sign-in URL for IAM...
- Nhập username và password ở B2 vừa tạo

<h3>Hướng dẫn tạo S3 trên AWS</h3>

- Truy cập https://aws.amazon.com/console/
- Trên thanh tìm kiếm gõ: **S3**
- Bấm vào Buckets -> Create Bucket
- Nhập tên Bucket
- Ở phần Block Public Access settings for this bucket
- Bỏ nhấp Block all public access
- Nhập chọn I acknowledge that the current settings might result in this bucket and the objects within becoming public.
- Create Bucket 
- Tạo thành công nhớ accessKeyId, secretKey, bucketName

<h2>Người viết hướng dẫn: Vinh Huynh </h2>


##### Connect me via: phucvinh710@gmail.com

##### Copyright &#169; 2023 vinh.huynh




