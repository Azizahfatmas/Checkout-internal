# Checkout-internal
<!doctype html>
<html lang="en">
 <head> 
  <meta charset="UTF-8"> 
  <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Cart Checkout</title> 
  <style>
   nav {
     height: 50px; 
     background-color: beige; 
     border: 1px solid black;   
   }
   span {
     font-size: 30px;
   }
   #b1 {
     float: right;
   }
   #svg1 {
     float: right; 
     width: 24px;
     height: 24px;
     viewbox: 0 0 24 24;
   }
   #svg2 { 
     float: right; 
     width: 24px;
     height: 24px;
     viewbox: 0 0 24 2;
   }
   div {
     padding-top: 50px; 
     display: flex;
   }
   #table1 {
     width: 60%;
   }
   #td1 {
     text-align: center;
   }
   #svg2 {
     width: 40px; 
     height: 40px;
     xmlns: http://www.w3.org/2000/svg;
     width: 16;
     height: 16;
     fill: currentColor;
     class: bi bi-check-circle;
     viewbox: 0 0 16 16;
   }
   #td2 {
     width: 500px;
   }
   #b1 {
     font-size: 20px;
     widht: 5px;
     height: 5px;
   }
   #th1 {
     font-size: 20px; 
     text-align: left;
   }
   #table2 {
     background-color: beige; 
     width: 30%; 
     margin-left: 30px; 
     padding: 20px; 
     height: 30%;
   }
   #td3 {
     colspan: 2; 
     text-align: left; 
     height: 30px;
   }
   #td4 {
     text-align: right;
   }
   #td5 {
     text-align: right;
   }
   #td6 {
     text-align: right;
   }
   #hr1 {
     color: beige;
   }
   form {
     method: post; 
     action: "";
     text-align: right;
     margin: 1em;
   }
  </style> 
 </head> 
 <body> 
  <nav> 
   <span>■</span> 
   <b>Site Name</b> 
   <a href="#">category 1</a> | 
   <a href="#">category 2</a> | 
   <a href="">category 3</a> | 
   <b id="b1">Cart (1)</b> 
   <svg id="svg1"> 
    <a href=""></a> 
    <path fill="currentColor" d="M17,18C15.89,18 15,18.89 15,20A2,2 0 0,0 17,22A2,2 0 0,0 19,20C19,18.89 18.1,18 17,18M1,2V4H3L6.6,11.59L5.24,14.04C5.09,14.32 5,14.65 5,15A2,2 0 0,0 7,17H19V15H7.42A0.25,0.25 0 0,1 7.17,14.75C7.17,14.7 7.18,14.66 7.2,14.63L8.1,13H15.55C16.3,13 16.96,12.58 17.3,11.97L20.88,5.5C20.95,5.34 21,5.17 21,5A1,1 0 0,0 20,4H5.21L4.27,2M7,18C5.89,18 5,18.89 5,20A2,2 0 0,0 7,22A2,2 0 0,0 9,20C9,18.89 8.1,18 7,18Z" /> 
   </svg> 
   <svg id="svg2"> 
    <a href=""></a> 
    <path fill="currentColor" d="M9.5,3A6.5,6.5 0 0,1 16,9.5C16,11.11 15.41,12.59 14.44,13.73L14.71,14H15.5L20.5,19L19,20.5L14,15.5V14.71L13.73,14.44C12.59,15.41 11.11,16 9.5,16A6.5,6.5 0 0,1 3,9.5A6.5,6.5 0 0,1 9.5,3M9.5,5C7,5 5,7 5,9.5C5,12 7,14 9.5,14C12,14 14,12 14,9.5C14,7 12,5 9.5,5Z" /> 
   </svg> 
  </nav> 
  <div> 
   <table id="table1"> 
    <tbody> 
     <tr> 
      <td id="td1"> 
       <svg id="svg2"> 
        <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z" /> 
        <path d="M10.97 4.97a.235.235 0 0 0-.02.022L7.477 9.417 5.384 7.323a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-1.071-1.05z" /> 
       </svg></td> 
      <td id="td2">Order 131217312<br><b id="b2">Thank you, Kenny!</b></td> 
     </tr> 
     <tr> 
      <td colspan="4"> 
       <hr></td> 
     </tr> 
     <tr> 
      <td>Your order is confirmed</td> 
     </tr> 
     <tr> 
      <td>We've accepted your order and wa're getting ot ready.</td> 
     </tr> 
     <tr> 
      <td colspan="4"> 
       <hr></td> 
     </tr> 
     <tr> 
      <th id="th1"><b>Coustomer Information</b></th> 
     </tr> 
     <tr> 
      <td><b>Shipping Address</b></td> 
      <td><b>Billing Address</b></td> 
     </tr> 
     <tr> 
      <td>Kenny Bostick</td> 
      <td>Kenny Bostick</td> 
     </tr> 
     <tr> 
      <td><a href="">12 Waldo Point Road <br>Mishauke, NY 11200 <br>United states</a> </td> 
      <td><a href="">12 Waldo Point Road <br>Mishauke, NY 11200 <br>United states</a> </td> 
     </tr> 
     <tr> 
      <td><b>Shipping Method</b></td> 
      <td><b>Payment Method</b></td> 
     </tr> 
     <tr> 
      <td>UPS Ground (Estimated Shipping <br>time of 3-6 days) </td> 
      <td><img src="assets/visa.png" alt="" width="30" height="20">Ending in 3217 - 23.60</td> 
     </tr> 
     <tr> 
      <td colspan="4"> 
       <hr></td> 
     </tr> 
    </tbody> 
   </table> 
   <table id="table2"> 
    <tbody> 
     <tr> 
      <td id="td3"><b>Summary (1 item)</b></td> 
     </tr> 
     <tr> 
      <td>Subtotal</td> 
      <td id="td4">$20.00</td> 
     </tr> 
     <tr> 
      <td>Shipping</td> 
      <td id="td5">$2.20</td> 
     </tr> 
     <tr> 
      <td>Est.Toxes</td> 
      <td id="td6">$1.40</td> 
     </tr> 
     <tr> 
      <td colspan="2"> 
       <hr id="hr1"></td> 
     </tr> 
     <tr> 
      <td>GIFt card or discount code</td> 
     </tr> 
     <tr> 
      <td> 
       <form> 
        <input type="text" name="code_discount" value=""> 
        <input type="submit" name="tombol" value="Apply"> 
       </form></td> 
     </tr> 
     <tr> 
      <td colspan="2"> 
       <hr style="color: yellow;"></td> 
     </tr> 
     <tr> 
      <td><b>Total</b></td> 
      <td style="text-align: right;"><b>$23.60</b></td> 
     </tr> 
     <tr> 
      <td colspan="2" style="text-align: center;"> <a href=""><button style="width: 100%; background-color: yellow;">Chekout</button></a> </td> 
     </tr> 
    </tbody> 
   </table> 
  </div> 
  <br> 
  <br> 
  <br> 
  <br> 
  <br> 
  <br> 
  <br> 
  <br> 
  <br> 
  <br> 
  <br> 
  <br> 
  <br> 
  <br> 
  <hr> 
  <div> 
   <table> 
    <tbody> 
     <tr> 
      <td>Site Name</td> 
      <td> <a herf="#">categoryX |</a> <a herf="#">categoryY |</a> <a herf="#">categoryZ |</a> </td> 
     </tr> 
     <tr> 
      <td colspan="2"> <img src="kartu atm.png"> <img src="kartu atm.png"> <img src="kartu debit.png" < td> </td> 
     </tr> 
    </tbody> 
   </table> 
  </div> 
  <div style="margin-left: auto;"> 
   <table> 
    <tbody> 
     <tr> 
      <td colspan="2">Stay in touch join ous newslater</td> 
     </tr> 
     <tr> 
      <td colspan="2"> <input type="text"> <button>Subscribe</button> </td> 
     </tr> 
    </tbody> 
   </table> 
  </div> 
 </body>
</html>
