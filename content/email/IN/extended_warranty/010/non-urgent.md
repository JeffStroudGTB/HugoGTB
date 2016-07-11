+++
markets = ["in"]
title = '''IN Extended Warranty 010 non urgent'''

preheader = ''''''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''http://google.com'''

[[module]] #Cover 06
path='email_modules/cover/06'
color='''white'''

  title = '''Let's keep a good thing going'''
  copy = '''Hello <%${user.CustomAttribute['FullName']}%><br><br>Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%>'s warranty will expire on <%${user.CustomAttribute['EWDate']}%>. Knowing you and your Ford are protected means the world to us, so we'd like to offer you an opportunity to extend your vehicle's warranty.<br><br>Our Extended Warranty Plans are designed specifically for your vehicle, and protect you from out-of-pocket bills. They cover major mechanical and electric failures, and are even transferrable - improving your vehicle's resale value.<br><br>We've got your back. Get in touch today and stay protected. '''
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
  icon1_image='''dealers_20160401'''
  alt1 = '''alt text'''
  icon2_url='''http://google.com'''
  icon2_image='''ford_credit_20160401'''
  alt2 = '''alt text'''
  icon3_url='''http://google.com'''
  icon3_image='''ford_assured_20160401'''
  alt3 = '''alt text'''
  icon4_url='''http://google.com'''
  icon4_image='''customer_care_number_20160401'''
  alt4 = '''alt text'''
  icon5_url='''http://google.com'''
  icon5_image='''rsa_no_20160401'''
  alt5 = '''alt text'''
+++