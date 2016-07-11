+++
markets = ["in"]
title = '''IN Service Reminder Declined 010 seasonal campaign'''

  preheader = ''''''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image = '''white'''
  url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 06
path='email_modules/cover/06'
color='''white'''

  title = '''Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> needs attention'''
  copy = '''We noticed that you declined an important part of your servicing at your last appointment. That's got us worried.<br><br>When you come into a Ford service centre, you're putting your vehicle into the best hands possible. Our trained technicians know the specifics of your Ford vehicle and only use genuine Ford parts.<br><br>As part of the Ford family, we've got your back. Visit us at a Ford dealer soon.'''
  cta1_text = '''GET A CALLBACK'''
  cta1_url_link = '''https://www.india.ford.com/ford-service/service-bookings'''
  cta2_text = '''FIND A DEALER'''
  cta2_url_link = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
  icon = '''ew'''

[[module]] #Service Status No Copy
path='email_modules/custom/svcstatus_nocopy'
color='white'

  toptitle='''Top Title White'''
  icon1='''ew'''
  title1='''Brakes'''
  subtitle1='''Good to go'''
  icon2='''ew'''
  title2='''Tyres'''
  subtitle2='''Good to go'''
  icon3='''ew'''
  title3='''Batteries'''
  subtitle3='''Service immediately'''
  
[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image = '''cashback_20160328'''
  url1 = '''http://www.google.com'''

[[module]] #Custom 02
path='email_modules/custom/02'
color='white'

  title1 = '''Service Price Promise'''
  text1 = '''We ensure that there are no surprises in your service cost. The price you see online is the price you pay.'''
  textlink1_text = '''Check service price'''
  textlink1_url_link = '''https://www.fordservicepricepromise.com/?extcmp=serca_101115_105328_fordind'''
  title2 = '''Pick Up &#38; Drop'''
  text2 = '''Stay home while we pick up, service, and return your vehicle to you. The easiest way to keep your Ford in top shape. '''
  title3 = '''Parts Cost Calculator'''
  text3 = '''We tell you exactly how much a replacement part will cost before you even visit the service centre.'''
  textlink2_text = '''Check parts price'''
  textlink2_url_link = '''https://partscalculator.fordind.com:1443/Fill_Field'''
  cta_text = '''FIND A DEALER'''
  cta_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image = '''4x4_20160613'''
  url2 = '''http://www.google.com'''

[[module]] #Cover 07
path='email_modules/cover/07'
color='''white'''

  title = '''Monsoon Campaign'''
  copy = '''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<br><br>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum'''
  cta_text = '''Click me!'''
  cta_url = '''http://google.com'''

[[module]] #Footer 4 Icons
path='email_modules/footer/4icons'
color='white'

  icon1_url='''http://google.com'''
  icon1_image='''dealers_20160401'''
  icon2_url='''http://google.com'''
  icon2_image='''ford_credit_20160401'''
  icon3_url='''http://google.com'''
  icon3_image='''customer_care_number_20160401'''
  icon4_url='''http://google.com'''
  icon4_image='''rsa_no_20160615'''
+++