+++
markets = ["in"]
title = '''IN Extended Warranty 010 urgent'''

preheader = ''''''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.india.ford.com'''

[[module]] #Cover 06
path='email_modules/cover/06'
color='''white'''

  title = '''Last chance to extend your warranty'''
  copy = '''Hello <%${user.CustomAttribute['FullName']}%><br><br>Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%>'s warranty will expire on <%${user.CustomAttribute['EWDate']}%>. Once it expires, it can't be extended.<br><br>Our Extended Warranty Plans are designed specifically for your vehicle, and protect you from out-of-pocket bills. They cover major mechanical and electric failures, and are even transferrable - improving your vehicle's resale value.<br><br>We've got your back. Get in touch today and stay protected.'''
  cta1_text = '''STAY COVERED'''
  cta1_url_link = '''www.india.ford.com/ford-service/solutions/extended-warranty'''
  cta2_text = '''GET A CALLBACK'''
  cta2_url_link = '''www.india.ford.com/callback/confirmation'''
  icon = '''ew'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image = '''cashback_20160328'''
  url_link = '''http://www.google.com'''

[[module]] #Footer 5 Icons
path='email_modules/footer/5icons'
color='white'

  icon1_url='''http://google.com'''
  icon1_image='''in_dealers_20160414'''
  alt1 = '''alt text'''
  icon2_url='''http://google.com'''
  icon2_image='''in_ford_credit_20160401'''
  alt2 = '''alt text'''
  icon3_url='''http://google.com'''
  icon3_image='''in_ford_assured_20160401'''
  alt3 = '''alt text'''
  icon4_url='''http://google.com'''
  icon4_image='''in_customer_care_number_20160401'''
  alt4 = '''alt text'''
  icon5_url='''http://google.com'''
  icon5_image='''in_rsa_no_20160615'''
  alt5 = '''alt text'''
    
[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++