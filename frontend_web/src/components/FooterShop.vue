<template >
  <!-- Remove the container if you want to extend the Footer to full width. -->
 <div class=" my-5 footer-container">
   <footer>
   <section class="text-center container mt-3">
     <div class="row row-cols-2 row-cols-sm-2 row-cols-md-3">
       <div class="col">
         <div class="mb-3"> 
         </div>
         <h5>MIỄN PHÍ GIAO HÀNG</h5>
         <p>Miễn Phí Giao Hàng Với Hoá Đơn Trên 900.000đ
         </p>
       </div>
       <div class="col">
         <div class="mb-3">
           <!-- <i class=" text-white bg-black border  rounded-circle p-3 fa-solid fa-screwdriver-wrench"></i> -->
         </div>
         <h5>BẢO HÀNH 1 NĂM</h5>
         <p>Hỗ trợ bảo hành sửa chửa 1 năm miễn phí</p>
       </div>
       <div class="col">
         <div class="mb-3">
           <font-awesome-icon :icon="['far', 'location-dot']" />
           <!-- <i class=" text-white bg-black border  rounded-circle p-3 fa-solid fa-shop"></i> -->
         </div>
         <h5>SHOWROOMS</h5>
         <p>Địa Chỉ: Hòa Hưng  Quận 10 TP HCM</p>
       </div>
 
 
     </div>
   </section>
   <section class="bg-black text-white">
     <div class="container py-3">
       <div class="row row-cols-2 row-cols-sm-2 row-cols-md-4">
         <div class="col">
           <h5>ĐƯỢC TRỢ GIÚP</h5>
           <a href="">
             <p>Tình trạng đặt hàng</p>
           </a>
           <a href="">
             <p>Vận chuyển</p>
           </a>
           <a href="">
             <p>Lợi nhuận</p>
           </a>
           <a href="">
             <p>Các lựa chọn thanh toán</p>
           </a>
           <a href="">
             <p>Liên hệ chúng tôi</p>
           </a>
 
         </div>
         <div class="col">
           <h5>Shop Phone</h5>
           <a href="">
             <p>Tin tức</p>
           </a>
           <a href="">
             <p>Các nhà tài trợ</p>
           </a>
           <a href="">
             <p>Sự chất lượng</p>
           </a>
         </div>	
         <div class="col">
           <h5>TỔNG TÀI HỖ TRỢ</h5>
           <a href="">
             <p>Gọi mua: 
               <span>1800.1090</span>
             </p>
           </a>
           <a href="">
             <p>Kỹ thuật: 
               <span>1800.1080</span>
             </p>
           </a>
           <a href="">
             <p>Bảo hành: 
               <span>1800.1070</span>
             </p>
           </a>
           <a href="">
             <p>Khiếu nại: 
               <span>1800.1060</span>
             </p>
           </a>
           
 
         </div>
         <div class="col">
           <h5>KHÁC</h5>
           <a href="">
             <p>Tìm một cửa hàng</p>
           </a>
           <a href="">
             <p>Trở thành một thành viên</p>
           </a>
           <a href="">
             <p>Gửi phản hồi</p>
           </a>
           <div class="row row-cols-md-4 "> 
             <!-- <div class="col society ">
               <a href="">
               <p><i class="fa-brands fas fa-facebook"></i></p>
               </a>
             </div>
             <div class="col society">
               <a href="">
               <p><i class="fa-brands fas fa-twitter"></i></p>
               </a>
             </div>
               <div class="col society">
               <a href="">
               <p><i class="fa-brands fas fa-instagram"></i></p>
               </a>
             </div> -->
           </div>
         </div>
 
       </div>
       </div>
   </section>
   <section class="bg-black text-white">
     <div class="container  py-3">
       <div class="row ">
         <!-- <div class="col">
           <p> <i class="fa-sharp fa-solid fa-location-dot"></i> Vietnam <i class="fa-regular fa-copyright"></i>
             2022 Nike, Inc. All Rights Reserved</p>
         </div> -->
         <div class="col text-center">
           <p><a href=""><span>Hướng dẫn</span></a> <a href=""><span>Điều khoản sử
                 dụng</span></a> <a href=""><span>Điều khoản bán hàng</span></a></p>
         </div>
       </div>
     </div>
   </section>
 </footer>
 
 </div>
 <!-- End of .container -->
 </template>
 <style>
 div.col>a{
     text-decoration: none;
    color: rgb(98, 97, 96);  
 }
 div.col>a:hover{
 color: white; 
 }   
 div.society>a>p>i{
     font-size: x-large;
 }
 div.col>p>a{
     text-decoration: none;
     color: rgb(98, 97, 96);  
 
 }
 div.col>p>a:hover{
  color: white;
 }
 div.col>a>p>span:hover{
     color: blue;
    }
 i.fa-facebook:hover{
     color: #3b5998;
 }
 i.fa-twitter:hover{
     color: #55acee;
 }
 i.fa-instagram:hover{
     color: #ac2bac;
 }
 li.itemLogin{
     display: inline;
 }
 ul.ulLogin{
     width: 300px;
 }
 .table-hover tbody tr:hover {
     background-color: #2d2dc8; /* Màu sắc khi hover */
     cursor: pointer; /* Thay đổi con trỏ chuột khi hover */
   }
.footer-container{
  background-color: #CCCC00;
}
  
 </style>