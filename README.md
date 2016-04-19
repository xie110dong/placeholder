# placeholder
placeholder的向下兼容，适配ie9等无placeholder属性  
1. js引用  
  - 引入jquery.min.js
  - 引入jquery.placeholder.js
2. html  
  <input class="my_class"  name="filename" placeholder="ph_name" />
3. javascript
  jQuery('input[placeholder]').placeholder();
