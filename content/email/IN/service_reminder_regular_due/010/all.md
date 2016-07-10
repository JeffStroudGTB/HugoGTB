+++
markets = [ "in" ]
title = '''IN Service Reminder Regular Due 010 All'''

preheader = '''When you purchase a Ford, you're not just buying a great vehicle - you're joining a family.'''

[[module]]
path='email_modules/header/logo'
color='white'

url='''http://google.com'''
image='''ford_credit_20160401'''

[[module]]
path='email_modules/cover/06'
color='''black'''

icon='''ew'''
title='''Black Title'''
copy='''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<br><br>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum'''
cta1_text='''Click Here!'''
cta1_url='''http://google.com'''
cta2_text='''Click me!'''
cta2_url='''http://google.com'''

[[module]]
path='email_modules/custom/06'
color='black'

custom_06_white_text = '''White Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<br><br>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum'''

[[module]]
path='email_modules/image/banner'
color='white'

image='''cashback_20160328'''
url='''http://google.com'''

[[module]]
path='email_modules/custom/02'
color='black'

custom_02_white_cta_text = '''CLICK HERE'''
custom_02_white_cta_url = '''http://google.com'''
custom_02_white_text1 = '''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'''
custom_02_white_text2 = '''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'''
custom_02_white_text3 = '''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'''
custom_02_white_textlink1_text = '''This is a link!'''
custom_02_white_textlink1_url = '''https://google.com'''
custom_02_white_textlink2_text = '''This is a link!'''
custom_02_white_textlink2_url = '''https://google.com'''
custom_02_white_title1 = '''Title 1'''
custom_02_white_title2 = '''Title 2'''
custom_02_white_title3 = '''Title 3'''

[[module]]
path='email_modules/cover/05'

color='''black'''
icon='''ew'''
title='''Black Title'''
copy='''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<br><br>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum'''
cta_text='''Click me!'''
cta_url='''http://google.com'''

[[module]]
path='email_modules/custom/01'
color='black'
custom_01_white_icon1 = '''ew'''
custom_01_white_icon2 = '''ew'''
custom_01_white_icon3 = '''ew'''
custom_01_white_text1 = '''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'''
custom_01_white_text2 = '''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'''
custom_01_white_text3 = '''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'''
custom_01_white_title = '''Custom 01 Title'''

[[module]]
path='email_modules/image/banner'
color='white'

image='''cashback_20160328'''
url='''http://google.com'''

[[module]]
path='email_modules/footer/4icons'
color='white'

icon1_url='''http://google.com'''
icon1_image='''ford_credit_20160401'''
icon2_url='''http://google.com'''
icon2_image='''ford_credit_20160401'''
icon3_url='''http://google.com'''
icon3_image='''ford_credit_20160401'''
icon4_url='''http://google.com'''
icon4_image='''ford_credit_20160401'''

[[module]]
path='email_modules/footer/in/social'
color='white'

[[module]]
path='email_modules/footer/in/online'
color='white'

+++

<%= partial "modules/#{lang}/head" %>

<%= partial "modules/#{lang}/header/logo" %>
<%= partial "modules/#{lang}/cover/06/white" %>
<%= partial "modules/#{lang}/custom/06/white" %>
<%= partial "modules/#{lang}/image/banner1", :locals => { :bannerimage => current_page.data.image_banner_image1, :bannerurl => current_page.data.image_banner_url1 }  %>
<%= partial "modules/#{lang}/custom/02/white"%>
<%= partial "modules/#{lang}/cover/05/white" %>
<%= partial "modules/#{lang}/custom/01/white"%>
<%= partial "modules/#{lang}/image/banner1", :locals => { :bannerimage => current_page.data.image_banner_image2, :bannerurl => current_page.data.image_banner_url2 }  %>
<%= partial "modules/#{lang}/footer/in/4icons" %>
<%= partial "modules/#{lang}/footer/in/social" %>
<%= partial "modules/#{lang}/footer/in/online" %>

<%= partial "modules/#{lang}/foot" %>