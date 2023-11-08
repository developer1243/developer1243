<!doctype html>
<html> 
 <head> 
  <title>HTML Widget Maker</title> 
  <style>
        #widget-container {
            width: 80%;
            margin: 0 auto;
        }
        .widget {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px 0;
            background-color: #f0f0f0;
        }
    </style> 
 </head> 
 <body> 
  <h1>HTML Widget Maker</h1> 
  <div id="widget-container"> 
   <div class="widget"> 
    <h2>Widget Title</h2> 
    <p>This is a sample widget.</p> 
   </div> 
  </div> 
  <h2>Create Your Widget</h2> <textarea id="widget-code" rows="10" cols="50" placeholder="Enter your HTML widget code here..."></textarea> <button onclick="createWidget()">Create Widget</button> 
  <div id="preview"> 
   <h2>Widget Preview</h2> 
  </div> 
  <script>
        function createWidget() {
            const widgetCode = document.getElementById("widget-code").value;
            const preview = document.g
                          
