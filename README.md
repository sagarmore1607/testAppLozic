# testAppLozic
load applozic within div


Download AppLozic Plugin from given url https://github.com/AppLozic/Applozic-Web-Plugin

create a new file "index.html" with
      
      <!DOCTYPE html>
      <html>
      <head>
        <title>AppLozic test with emojis</title>
        <script src="js/jquery-2.2.2.min.js"></script> /////load jquery
      </head>
      <body>
      <div id="docload"></div>// div to load page within it
        <script>
          $('#docload').load('fullview.html'); // Load fullview.html in div
        </script>
      </body>
      </html>
      
 in "Applozic-Web-Plugin/message/fullview/".
 
 Open "Applozic-Web-Plugin/message/fullview/index.html". The plugin works fine but when it comes to "emoji" it is showing codes instead emoji in both to reciever and in notification popup.
