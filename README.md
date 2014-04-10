<pre>
vagouzhou.github.io: web app demo testing.

Test GetUserMedia in Local video
==============================================
we also can run sever in local by python (need python 2.7),input command as below in terminal console
<b>python pythonssl.py</b>

then access it in browser for testing.<br>
e.g. https://localhost:4443/firefox/firefox_gum_test.html


Test screen sharing through peer connection. 
==============================================
we can directly use https://apprtc.appspot.com
  # In screen sending end.
        copy this link in firefox <b>https://apprtc.appspot.com/?video=mozMediaSource=screen&audio=false</b>
        It will share screen. and generate one room number .
        e.g.    
        <b>https://apprtc.appspot.com/?r=01393400&audio=false&video=mozMediaSource=screen</b>
          room number is <b>01393400</b>
  
  # In receiving end.
    input link with room number <b>https://apprtc.appspot.com/?r=01393400</b>
</pre>
