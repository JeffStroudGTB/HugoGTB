+++
markets = [ "in" ]
title = '''IN Extended Warranty 010 urgent'''

preheader = '''preheader goes here'''

[[module]]
  path='email_modules/header/logo'
  color='white'

  image = '''white'''
  url = '''https://www.india.ford.com'''

[[module]]
  path='email_modules/cover/06'
  color='white'

  copy = '''Hello <%${user.CustomAttribute['FullName']}%><br><br>Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%>'s warranty will expire on <%${user.CustomAttribute['EWDate']}%>. Once it expires, it can't be extended.<br><br>Our Extended Warranty Plans are designed specifically for your vehicle, and protect you from out-of-pocket bills. They cover major mechanical and electric failures, and are even transferrable - improving your vehicle's resale value.<br><br>We've got your back. Get in touch today and stay protected.'''
  cta1_text = '''STAY COVERED'''
  cta1_url = '''www.india.ford.com/ford-service/solutions/extended-warranty'''
  cta2_text = '''GET A CALLBACK'''
  cta2_url = '''www.india.ford.com/callback/confirmation'''
  icon = '''ew'''
  title = '''Last chance to extend your warranty'''

[[module]]
  path='email_modules/image/banner'
  color='white'

  image = '''cashback_20160328'''
  url = '''http://www.google.com'''

[[module]]
  path='email_modules/footer/5icons'
  color='white'

  icon1_image = '''dealers_20160401'''
  icon2_image = '''ford_credit_20160401'''
  icon3_image = '''ford_assured_20160401'''
  icon4_image = '''customer_care_number_20160401'''
  icon5_image = '''rsa_no_20160401'''

[[module]]
  path='email_modules/footer/in/social'
  color='white'

[[module]]
  path='email_modules/footer/in/online'
  color='white'

+++