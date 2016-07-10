+++
markets = ["ph"]
title = '''PH Service Reminder First 010 All'''

preheader = '''Your Ford Vehicle must be nearly ready for its 10,000km service.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  header_logo_image = '''white'''
  header_logo_url = '''http://www.ford.com.ph/'''

[[module]] #Cover 06
path='email_modules/cover/06'
color='''black'''

  cover_06_white_title = '''Time flies when you're having fun'''
  cover_06_white_copy = '''Hello <%${user['FirstName']}%><br><br>Your Ford <%${user.CustomAttribute['Model']}%> must be nearly ready for its 10,000km service. This is the first service of the lifetime maintenance plan for your Ford <%${user.CustomAttribute['Model']}%>, designed to ensure that it always operates at its optimum.<br><br>And while you’re there, don’t forget to pick up a weathershield, so you can enjoy fresh air anytime - even in a downpour.<br><br>XXXXxxxxxxxxx'''
  cover_06_white_cta1_text = '''CALL'''
  cover_06_white_cta1_url = '''http://google.com'''
  cover_06_white_cta2_text = '''FIND A DEALER'''
  cover_06_white_cta2_url = '''http://www.ford.com.ph/locate-a-dealer/'''
  cover_06_white_icon = '''ew'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image_banner_image = '''cashback_20160328'''
  image_banner_url = '''http://www.google.com'''

[[module]] #Cover 05
path='email_modules/cover/05'
color='''black'''

  cover_05_fordblue_title = '''We're there for you, anytime'''
  cover_05_fordblue_copy = '''It's good to know that when you drive your Ford, we're ready to help when you need it. Our Emergency Roadside Assistance is on-call, 24 hours a day, 7 days a week, and free of charge, in yousership. Call us whenever you need a hand if you run out of fuel, have a flat tyre, need help with a vehicle emergency and more. Just remember this number:(02) 459-4723'''
  cover_05_fordblue_cta_text = '''FIND OUT MORE'''
  cover_05_fordblue_cta_url:http://www.ford.com.ph/buying/assistance'''
  cover_05_fordblue_icon = '''ew'''

[[module]] #Cover 05
path='email_modules/cover/05'
color='''black'''

  cover_05_slatescreen_title = '''Premium Extended Warranty'''
  cover_05_slatescreen_copy = '''With quality service and genuine parts, a Premium Extended Warranty is the best choice for owners, like you, who want to go the distance with their vehicle. <br><br>Warranties are available for up to 5 years, and save you money on servicing. They may also be fully transferrable to the next vehicle owner, helping improve re-sale value.'''
  cover_05_slatescreen_cta_text = '''GET COVERED'''
  cover_05_slatescreen_cta_url = '''http://www.ford.com.ph/buying/warranty'''
  cover_05_slatescreen_icon = '''ew'''

[[module]] #Split 02
path='email_modules/split/02'
color='black'

  split_02_green_title = '''Worry-free servicing'''
  split_02_green_copy = '''Keep your Ford running at its best, with our Scheduled Service Plan.<br><br>Professional maintenance for up to five years.<br><br>Protection against price rises on parts and labor.<br><br>Service plans are customizable.'''
  split_02_green_cta_text = '''LEARN MORE'''
  split_02_green_cta_url = '''http://www.ford.com.ph/buying/scheduledserviceplan'''
  split_02_green_cta_icon = '''play'''
  split_02_green_image = '''tms_2060328_tile'''

[[module]] #Dual 02
path='email_modules/dual/02'
color='white'

  dual_02_white_icon1 = '''ew'''
  dual_02_white_title1 = '''Book it now'''
  dual_02_white_cta1_text = '''Call your Ford Dealer on<%${user.CustomAttribute['Work_Phone']}%>'''
  dual_02_white_cta1_url = '''http://google.com'''
  dual_02_white_cta2_text = '''Find your nearest Ford Dealer'''
  dual_02_white_cta2_url = '''http://www.ford.com.ph/locate-a-dealer/'''
  dual_02_white_icon2 = '''ew'''
  dual_02_white_title2 = '''Anything changed? '''
  dual_02_white_copy = '''Update your details now so you don't miss our latest offers.'''
  dual_02_white_cta3_text = '''UPDATE NOW'''
  dual_02_white_cta3_url = '''https://www.ford.com.ph/owner/login'''

[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++