---
title: Code Test Page
permalink: /permalink/
description: ""
---


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
      background: #7c62c9;
      cursor: pointer;
    }
    

    .tab .content {
      background: #fff;
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


     
    <div class="tab">
      <input id="tab-1" type="checkbox">
      <label for="tab-1">கதையோடு விளையாடு, தமிழோடு உறவாடு!</label>
      <div class="content">
       <img src="/images/Jeeva2.png">
				<p style="text-align:&nbsp;center">திருவாட்டி ஜீவா ரகுநாத், AKT Creations நிறுவனம்</p>
				<div style="text-align:&nbsp;center"> 
				<a href="/workshops/ms-jeeva-raghunath">காண்க: இணையப் பயிலரங்கம்</a>
				</div>
			</div>
    </div>
    
    <!-- SECOND TAB -->
    <div class="tab">
      <input id="tab-2" type=" சிறுவர் பாடல்கள்வழியாகவும் விளையாட்டுகள்வழியாகவும் கருத்துப்பரிமாற்றமும் தமிழ்மொழி கற்றல் கற்பித்தலும்">
      <label for="tab-2">Tab 2</label>
      <div class="content"><p>புலவர் வெற்றிச்செழியன், முதல்வர், பாவேந்தர் தமிழ்வழி மழலையர் தொடக்கப்பள்ளி</p></div>
    </div>
    
    <!-- THIRD TAB -->
    <div class="tab">
      <input id="tab-3" type="checkbox">
      <label for="tab-3">Tab 3</label>
      <div class="content"><p>A circumstance strikes a   deserved trap.</p></div>
    </div>
    

