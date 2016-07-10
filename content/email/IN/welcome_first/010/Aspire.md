+++
markets = [ "in" ]
title = '''IN Welcome First Aspire 010 All'''

preheader = '''We love having you in the family. There's nothing quite like a new car. So it really means a lot to us that you chose another Ford.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  header_logo_image = '''white'''
  header_logo_url = '''https://www.india.ford.com'''

[[module]] #Cover 10
path='email_modules/cover/10'
color='white'

  cover_10_white_copy = '''There's nothing quite like a new car. And we want to thank you for making yours a Ford. <br><br>As part of the Ford family, you'll be hearing from us from time to time, but only with information we think you'd find helpful. And that's a promise.'''
  cover_10_white_title = '''Hope you're enjoying the ride'''

[[module]] #Image Banner
path='email_modules/image/banner'
color='white'

  image_banner_image = '''cashback_20160328'''
  image_banner_url = '''http://www.google.com'''

[[module]] #Cover 10
path='email_modules/cover/10'
color='white'

  cover_10_whiteg_copy = '''Keep your vehicle in top shape with us. Enjoy a free inspection and a car wash - on us - within the first 3 months or 2500 kilometers, whichever comes first. <br><br>Contact <%${user.CustomAttribute['Dealer_Name']}%> on <%${user.CustomAttribute['Dealer_Contact']}%> for more information.'''
  cover_10_whiteg_title = '''Your Free First Service'''

[[module]] #Cover 05
path='email_modules/cover/05'
color='white'

  cover_05_green_copy = '''Extend your Ford Aspire's warranty up to 5 years and enjoy worry-free driving. Your warranty protects your Ford against mechanical and electrical failures, and labour charges too1.'''
  cover_05_green_cta_text = '''GET PEACE OF MIND'''
  cover_05_green_cta_url = '''http://www.india.ford.com/ford-service/solutions/extended-warranty'''
  cover_05_green_icon = '''ew'''
  cover_05_green_title = '''Extended Peace of Mind'''

[[module]] #Split 01
path='email_modules/split/01'
color='white'

  split_01_white_copy = '''Make your Ford Aspire your own, with Ford Genuine Accessories that define your style. From the chrome kit to the rear spoiler - customise your Ford with us.'''
  split_01_white_cta_icon = '''play'''
  split_01_white_cta_text = '''MAKE IT YOURS!'''
  split_01_white_cta_url = '''http://www.india.ford.com/cars/figoaspire/accessories/exterior'''
  split_01_white_image = '''tms_20160328'''
  split_01_white_title = '''Time to Accessorise'''

[[module]] #Owner App Image Right
path='email_modules/custom_ownerapp_imgr'
color='white'

  owner_app_imgr_cta1_text = '''iOS'''
  owner_app_imgr_cta1_url = '''https://itunes.apple.com/in/app/ford-owners/id990342351?mt=8'''
  owner_app_imgr_cta2_text = '''Android'''
  owner_app_imgr_cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en'''
  owner_app_imgr_image = '''owner_app_20160328'''
  owner_app_imgr_text = '''Owning a Ford has never been easier, thanks to the Ford Owners app&#58;<br/><br/>&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Use the service checklist<br/>&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Access Roadside Assistance<br/>&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Watch videos about your Ford<br/>&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Find a dealer near you'''
  owner_app_imgr_title = '''Ford Owner App'''

[[module]] #Dual 04
path='email_modules/dual/04'
color='white'

  dual_04_white_copy1 = '''Download your Owners Manual on your device for access anytime anywhere.'''
  dual_04_white_copy2 = '''Your Ford Aspire comes with Ford SYNC® for hands-free control while you drive.'''
  dual_04_white_cta1a_text = '''DOWNLOAD NOW'''
  dual_04_white_cta1a_url = '''http://www.india.ford.com/owner'''
  dual_04_white_cta2a_text = '''LEARN ABOUT SYNC&#174'''
  dual_04_white_cta2a_url = '''http://www.india.ford.com/sync'''
  dual_04_white_icon1 = '''ew'''
  dual_04_white_icon2 = '''ew'''
  dual_04_white_title1 = '''Owner Manual'''
  dual_04_white_title2 = '''Get In SYNC&#174'''


[[module]] #Footer 4 Icons
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

<%= partial "modules/#{lang}/" %>
<%= partial "modules/#{lang}/cover/10/white" %>
<%= partial "modules/#{lang}/cover/10/white" %>
<%= partial "modules/#{lang}/image/banner" %>
<%= partial "modules/#{lang}/cover/10/whiteg" %>
<%= partial "modules/#{lang}/cover/05/green" %>
<%= partial "modules/#{lang}/split/01/white" %>
<%= partial "modules/#{lang}/custom/owner_app/imgr/black" %>
<%= partial "modules/#{lang}/dual/04/white"%>
<%= partial "modules/#{lang}/footer/in/4icons" %>
<%= partial "modules/#{lang}/footer/in/social" %>
<%= partial "modules/#{lang}/footer/in/online" %>


<%= partial "modules/#{lang}/foot" %>