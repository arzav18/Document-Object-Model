# Document-Object-Model

DOM : It basically catalogs the web page into indivisual objects that we can select and manipulate.

Inline Javascript: 

<body onload = "alert('hello')">
  
onload: It is an attribute. This means when the body of our website gets loaded up, then the Javascript placed inside these 2 quotation marks will get carried out. 

Downsides: 
  1) It's not very modular
  2) It's difficult to debug
  3) Not a good practice. 

  
Internal Javascript: 
  
<script type = "text/javascript">    Everything inside it will be a javascript code. 
  alert("Hello");
  </script>
  
  
External Javascript: 
      
  <script src = "index.js" charset="utf-8"></script>
  
