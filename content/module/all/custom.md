---
title: Custom All
layout: standard

preheader: 

custom_01_white_title: Custom 01 Title
custom_01_white_icon1: ew
custom_01_white_text1: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
custom_01_white_icon2: ew
custom_01_white_text2: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
custom_01_white_icon3: ew
custom_01_white_text3: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

custom_02_white_title1: Title 1
custom_02_white_text1: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
custom_02_white_textlink1_text: This is a link!
custom_02_white_textlink1_url: https://google.com
custom_02_white_title2: Title 2
custom_02_white_text2: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
custom_02_white_title3: Title 3
custom_02_white_text3: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
custom_02_white_textlink2_text: This is a link!
custom_02_white_textlink2_url: https://google.com
custom_02_white_cta_text: CLICK HERE
custom_02_white_cta_url: http://google.com

custom_03_darkblue_lightblue_image1: science_of_truck_20160328
custom_03_darkblue_lightblue_cta1_text: Click Here For Details
custom_03_darkblue_lightblue_cta1_url: http://google.com
custom_03_darkblue_lightblue_cta1_icon: play
custom_03_darkblue_lightblue_image2: tms_20160328
custom_03_darkblue_lightblue_cta2_text: Click Here for 2nd Details
custom_03_darkblue_lightblue_cta2_url: http://bing.com
custom_03_darkblue_lightblue_cta2_icon: play


custom_05_white_title1: Title 1
custom_05_white_icon1: ew
custom_05_white_text1: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
custom_05_white_title2: Title 2
custom_05_white_icon2: ew
custom_05_white_text2: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
custom_05_white_title3: Title 3
custom_05_white_icon3: ew
custom_05_white_text3: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
custom_05_white_title4: Title 4
custom_05_white_icon4: ew
custom_05_white_text4: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore

custom_06_white_text: White Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<br><br>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

---

<%= partial "modules/#{lang}/head" %>

<p>Custom 01</p>
<%= partial "modules/#{lang}/custom/01/white"%>
<p>Custom 02</p>
<%= partial "modules/#{lang}/custom/02/white"%>
<p>Custom 03</p>
<%= partial "modules/#{lang}/custom/03/darkblue_lightblue" %>
<p>Custom 05</p>
<%= partial "modules/#{lang}/custom/05/white"%>
<p>Custom 06</p>
<%= partial "modules/#{lang}/custom/06/white" %>

<%= partial "modules/#{lang}/foot" %>