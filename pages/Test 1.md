---
title: Test 1
permalink: /permalink/
description: ""
---
<html>
<head>
  <style>
		   .tab, .tab * {
      font-family: arial, sans-serif;
      box-sizing: border-box;
    }
    .tab { max-width: 600px; }
    
   
    .tab input { display: none; }
    
  
    .tab label {
   
      position: relative; 
      display: block;
      width: 100%;
      margin-top: 10px;
      padding: 10px;
     
   
      font-weight: 700;
      color: #fff;
      background: #2d5faf;
      cursor: pointer;
    }
    

    .tab .content {
      background: #ccdef9;
      overflow: hidden;
      transition: max-height 0.3s;
      max-height: 0;
    }
    .tab .content p { padding: 10px; }
    
  
    .tab input:checked ~ .content { max-height: 100vh; }
    
  
    .tab label::after {
   
      display: block;  
      content: "\25b6";
     
    
      position: absolute;
      right: 10px; top: 10px;
     
   
      transition: all 0.4s;
    }
     
   
    .tab input:checked ~ label::after { transform: rotate(90deg); }
	</style>
</head>
<body>

    <div class="tab">
      <input id="tab-1" type="checkbox">
      <label for="tab-1">Tab 1</label>
      <div class="content"><p>Next to the risk dictates a nurse.</p></div>
    </div>
    
    <!-- SECOND TAB -->
    <div class="tab">
      <input id="tab-2" type="checkbox">
      <label for="tab-2">Tab 2</label>
      <div class="content"><p>Should the pace attack?</p></div>
    </div>
    
    <!-- THIRD TAB -->
    <div class="tab">
      <input id="tab-3" type="checkbox">
      <label for="tab-3">Tab 3</label>
      <div class="content"><p>A circumstance strikes a   deserved trap.</p></div>
    </div>
    
</body>
</html>