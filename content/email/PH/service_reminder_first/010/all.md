+++
markets = ["ph"]
title = '''PH Service Reminder First 010 All'''

preheader = '''Your Ford Vehicle must be nearly ready for its 10,000km service.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''http://www.ford.com.ph/'''

[[module]] #Cover 06
path='email_modules/cover/06'
color='''white'''

  title = '''Time flies when you're having fun'''
  copy = '''Hello <%${user['FirstName']}%><br><br>Your Ford <%${user.CustomAttribute['Model']}%> must be nearly ready for its 10,000km service. This is the first service of the lifetime maintenance plan for your Ford <%${user.CustomAttribute['Model']}%>, designed to ensure that it always operates at its optimum.<br><br>And while you’re there, don’t forget to pick up a weathershield, so you can enjoy fresh air anytime - even in a downpour.<br><br>XXXXxxxxxxxxx'''
  cta1_text = '''CALL'''
  cta1_url = '''http://google.com'''
  cta2_text = '''FIND A DEALER'''
  cta2_url = '''http://www.ford.com.ph/locate-a-dealer/'''
  icon = '''ew'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image = '''cashback_20160328'''
  url_link = '''http://www.google.com'''

[[module]] #Cover 05
path='email_modules/cover/05'
color='''fordblue'''

  title = '''We're there for you, anytime'''
  copy = '''It's good to know that when you drive your Ford, we're ready to help when you need it. Our Emergency Roadside Assistance is on-call, 24 hours a day, 7 days a week, and free of charge, in yousership. Call us whenever you need a hand if you run out of fuel, have a flat tyre, need help with a vehicle emergency and more. Just remember this number:(02) 459-4723'''
  cta_text = '''FIND OUT MORE'''
  cta_url = '''http://www.ford.com.ph/buying/assistance'''
  icon = '''ew'''

[[module]] #Cover 05
path='email_modules/cover/05'
color='''slatescreen'''

  title = '''Premium Extended Warranty'''
  copy = '''With quality service and genuine parts, a Premium Extended Warranty is the best choice for owners, like you, who want to go the distance with their vehicle. <br><br>Warranties are available for up to 5 years, and save you money on servicing. They may also be fully transferrable to the next vehicle owner, helping improve re-sale value.'''
  cta_text = '''GET COVERED'''
  cta_url = '''http://www.ford.com.ph/buying/warranty'''
  icon = '''ew'''

[[module]] #Split 02
path='email_modules/split/02'
color='green'

  title = '''Worry-free servicing'''
  copy = '''Keep your Ford running at its best, with our Scheduled Service Plan.<br><br>Professional maintenance for up to five years.<br><br>Protection against price rises on parts and labor.<br><br>Service plans are customizable.'''
  cta_text = '''LEARN MORE'''
  cta_url = '''http://www.ford.com.ph/buying/scheduledserviceplan'''
  cta_icon = '''play'''
  image = '''tms_2060328_tile'''

[[module]] #Dual 02
path='email_modules/dual/02'
color='white'

  icon1 = '''ew'''
  title1 = '''Book it now'''
  cta1_text = '''Call your Ford Dealer on<%${user.CustomAttribute['Work_Phone']}%>'''
  cta1_url = '''http://google.com'''
  cta2_text = '''Find your nearest Ford Dealer'''
  cta2_url = '''http://www.ford.com.ph/locate-a-dealer/'''
  icon2 = '''ew'''
  title2 = '''Anything changed? '''
  copy = '''Update your details now so you don't miss our latest offers.'''
  cta3_text = '''UPDATE NOW'''
  cta3_url = '''https://www.ford.com.ph/owner/login'''

[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++