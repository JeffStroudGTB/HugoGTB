+++
title = '''IN Repurchase 010 offer'''

preheader = ''''''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url = '''https://www.india.ford.com'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image_banner_image = '''cashback_20160328'''
  image_banner_url = '''http://www.google.com'''

[[module]] #Cover 08
path='email_modules/cover/08'
color='''white'''
  
  cover_08_white_title = '''Meet the latest Ford vehicles'''
  cover_08_white_copy = '''We noticed you've been driving your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> for a while now and might be thinking about purchasing a new Ford.<br><br>At Ford, we design vehicles around you. That's why many new Ford vehicles - like EcoSport, Next-Gen Figo and Aspire - come with the SYNC® voice-activation system.<br><br>Just pair your smartphone and use simple voice commands to make calls, listen to text messages, and play your favourite music.<br><br>How smart is that? Come take a test drive and find out for yourself.'''
  cover_08_white_cta1_text = '''FIND A DEALER'''
  cover_08_white_cta1_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_%3C%${user.CustomAttribute['DMCDATE']}%%3E_APMKTC4L_%3C%${user.CustomAttribute['DMCCAMPAIGN']}%%3E_locate-dealer'''
  cover_08_white_cta2_text = '''LEARN MORE'''
  cover_08_white_cta2_url = '''http://www.india.ford.com/sync'''

[[module]] #Cover 05
path='email_modules/cover/05'
color='''lightblue'''

  cover_05_lightblue_title = '''Ford Live Chat'''
  cover_05_lightblue_copy = '''Ford Live Chat is now online! Get real-time answers from our team of Ford Advisors between 9am to 8pm. '''
  cover_05_lightblue_cta_text = '''START CHATTING'''
  cover_05_lightblue_cta_url = '''https://ford-livechat.s3ae.com/in/chat.php?a=1e4b8&intgroup=c3VwcG9ydA__&hg=Pw__&hcgs=MQ__&htgs=MQ__'''
  cover_05_lightblue_icon = '''ew'''

[[module]] #Cover 05
path='email_modules/cover/05'
color='''white'''

  cover_05_white_title = '''Your Profile Details'''
  cover_05_white_copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br>Email&#58; <%${user.CustomAttribute['RealEmail']}%><br>Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br>Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br><br>Anything changed?'''
  cover_05_white_cta_text = '''UPDATE YOUR DETAILS'''
  cover_05_white_cta_url = '''https://www.india.ford.com/profile-update-form?fbdata=req_firstName=<% ${user['FirstName']} %>||req_lastName=<% ${user['LastName']} %>||req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>||req_EmailID=<% ${user.CustomAttribute['RealEmail']} %>||req_BuildingNo=<% ${user.CustomAttribute['Address_1']} %>||req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>||req_Area=<% ${user.CustomAttribute['Area']} %>||req_Landmark=<% ${user.CustomAttribute['Landmark']} %>||req_city=<% ${user.CustomAttribute['City']} %>||req_State=<% ${user.CustomAttribute['State']} %>||req_postCode=<% ${user.CustomAttribute['Post_Code']} %>'''
  cover_05_white_icon = '''ew'''

[[module]]
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