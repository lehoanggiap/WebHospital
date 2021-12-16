# WebHospital
### Ae nhớ bỏ code html css header footer vào mỗi trang ae làm để tránh trùng tên class
### Css ae code internal hoặc inline 
### Code xog trang: 
### Thẻ a đổi href thành /tên trang  (không có đuôi html nữa)
###  Thẻ img đổi href thành /HinhAnh/tên hình 
###  Làm xog xóa code html css của header footer 
### Đổi đuôi file thành .ejs 
###  Ví dụ giống v:

 <%- include("./partials/head.ejs") %> => này là đầu trang mấy cái như html r link ...
<style>
   code css 
</style>
</head>
<body>
   <%- include("./partials/nav.ejs") %> => header
   code html 

<%- include("./partials/footer.ejs") %> => footer

<script>
    code javascript
</script>
</body>
</html> 

![image](https://user-images.githubusercontent.com/86466679/146379404-5405735c-7b15-4fab-94ff-b59afc984d9a.png)
