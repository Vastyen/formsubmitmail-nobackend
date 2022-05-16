# Form Mail Submit with HTML 

Just HTML, not Backend, not Php, not Node.js

Replace the keys and the text inside for your settings.

<form class="form" target="_blank" action="https://formsubmit.com/{mailhere}" method="POST">

Example 
                    
               <form class="form" target="_blank" action="https://formsubmit.com/bastian.escribano@usach.cl" method="POST">

               To recive emails from the current website the method need confirm the e-mail.

Added anothers for no-captcha form 
              <input type="hidden" name="_captcha" value="false">

              If you wan't the captcha, just remove the line.
    
No spam box
             <input type="text" name="_honey" style="display:none">
    
Thank you page 
              <input type="hidden" name="_next" value="nextpage">
              The nextpage it's de the sucesfull/thankyou submit page.
