+++
title = '''IN Anniversary 010 All'''


preheader = ''''''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url = '''https://www.india.ford.com/'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image_banner_image = '''cashback_20160328'''
  image_banner_url = '''www.google.com'''

[[module]] #Cover 10
path='email_modules/cover/10'
color='''white'''
 
  cover_10_white_title = '''How are you celebrating?'''
  cover_10_white_copy = '''Hello <%${user.CustomAttribute['FullName']}%><br/><br/>It has been nearly one year for you and your Ford <%${user.CustomAttribute['Selected_Vehicle']}%>! We sincerely hope the drive has been smooth, rewarding, and - most of all - enjoyable.<br/><br/>As part of the Ford family, we'll continue to look out for you this coming year. That's why we created the Ford Owners app - to make owning a Ford easier than ever.  '''
  
[[module]] #Custom 05
path='email_modules/custom/05'
color='white'

  custom_05_white_title1 = '''Service Checklist'''
  custom_05_white_icon1 = '''ew'''
  custom_05_white_text1 = '''Know what needs to be serviced, when.'''
  custom_05_white_title2 = '''24h Roadside Assistance'''
  custom_05_white_icon2 = '''ew'''
  custom_05_white_text2 = '''Because we'll never leave you stranded. 	'''
  custom_05_white_title3 = '''How-to Videos'''
  custom_05_white_icon3 = '''ew'''
  custom_05_white_text3 = '''Step-by-step guide to Ford tech. '''
  custom_05_white_title4 = '''Dealer Locator'''
  custom_05_white_icon4 = '''ew'''
  custom_05_white_text4 = '''Because we're always here for you.'''

[[module]] #Cover 12
path='email_modules/cover/12'
color='''white'''

  cover_12_white_copy = '''Download the app now, absolutely free, and have all of this important information and more at your fingertips, anywhere you and your Ford go.'''
  cover_12_white_cta1_text = '''iOS'''
  cover_12_white_cta1_url = '''https://itunes.apple.com/in/app/ford-owners/id990342351?mt=8'''
  cover_12_white_cta2_text = '''ANDROID'''
  cover_12_white_cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en'''

[[module]] #Cover 05
path='email_modules/cover/05'
color='''white'''

  cover_05_white_title = '''Your Profile Details'''
  cover_05_white_copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br>Email&#58; <%${user.CustomAttribute['RealEmail']}%><br>Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br>Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br><br>Anything changed?'''
  cover_05_white_cta_text = '''UPDATED YOUR DETAILS'''
  cover_05_white_cta_url = '''https://www.india.ford.com/profile-update-form?fbdata=req_firstName=<% ${user['FirstName']} %>||req_lastName=<% ${user['LastName']} %>||req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>||req_EmailID=<% ${user.CustomAttribute['RealEmail']} %>||req_BuildingNo=<% ${user.CustomAttribute['Address_1']} %>||req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>||req_Area=<% ${user.CustomAttribute['Area']} %>||req_Landmark=<% ${user.CustomAttribute['Landmark']} %>||req_city=<% ${user.CustomAttribute['City']} %>||req_State=<% ${user.CustomAttribute['State']} %>||req_postCode=<% ${user.CustomAttribute['Post_Code']} %>'''
  cover_05_white_icon = '''ew'''

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