

<b>##Test screen sharing </b>
==============================================
<pre>
<b>##how to get package</b>
====================================================
1. building it by source code 
2. get binary pacakge from https://www.dropbox.com/sh/5e642hv4d3hm1wo/AABtnEOITHH3Y-pocHY6SItOa


Note:
<b>Please use "about:config" to add "localhost" ,"apprtc.appspot.com", or "vagouzhou.github.io" into "media.getusermedia.screensharing.allowed_domains"</b>

<b>##Test GetUserMedia by github site.</b>
====================================================
vagouzhou.github.io/firefox/firefox_gum_test.html

<b>##Test GetUserMedia in Local video</b>
==============================================
we also can run sever in local by python (need python 2.7),input command as below in terminal console
<b>python pythonssl.py</b>

then access it in browser for testing.<br>
e.g. https://localhost:4443/firefox/firefox_gum_test.html


<b>##Test screen sharing through peer connection. </b>
==============================================
we can directly use https://apprtc.appspot.com
  # In screen sending end.
        copy this link in firefox <b>https://apprtc.appspot.com/?audio=false&video=mozMediaSource=screen,minWidth=1366,minHeight=768,maxWidth=1366,maxHeight=768&</b>
        It will share screen. and generate one room number .
        e.g.    
        <b>https://apprtc.appspot.com/?r=84903152&audio=false&video=chromeMediaSource=screen,minWidth=1366,minHeight=768,maxWidth=1366,maxHeight=768</b>
          room number is <b>84903152</b>
  
  # In receiving end.
    input link with room number <b>https://apprtc.appspot.com/?r=84903152</b>

</pre>

<b>##Test screen sharing + open264 </b>
==============================================
1. building it by source code https://github.com/ruil2/gecko-dev/tree/screen_gmp.
2. get binary pacakge from https://www.dropbox.com/sh/5e642hv4d3hm1wo/AABtnEOITHH3Y-pocHY6SItOa
3. get plugin from https://github.com/ruil2/gecko-dev/tree/screen_gmp/gmp-openh264
   Now, load plugin from , copy  gmp-openh264 to below.
        windows: c:/tmp/GMP/
        mac/linux: ~/tmp/GMP/

