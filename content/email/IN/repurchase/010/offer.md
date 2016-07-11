+++
markets = ["in"]
title = '''IN Repurchase 010 offer'''

preheader = ''''''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.india.ford.com'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image = '''cashback_20160328'''
  url_link = '''http://www.google.com'''

[[module]] #Cover 08
path='email_modules/cover/08'
color='''white'''
  
  title = '''Meet the latest Ford vehicles'''
  copy = '''We noticed you've been driving your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> for a while now and might be thinking about purchasing a new Ford.<br><br>At Ford, we design vehicles around you. That's why many new Ford vehicles - like EcoSport, Next-Gen Figo and Aspire - come with the SYNC® voice-activation system.<br><br>Just pair your smartphone and use simple voice commands to make calls, listen to text messages, and play your favourite music.<br><br>How smart is that? Come take a test drive and find out for yourself.'''
  cta1_text = '''FIND A DEALER'''
  cta1_url_link = '''http://www.india.ford.com/locate-dealer?emailid=EDM_%3C%${user.CustomAttribute['DMCDATE']}%%3E_APMKTC4L_%3C%${user.CustomAttribute['DMCCAMPAIGN']}%%3E_locate-dealer'''
  cta2_text = '''LEARN MORE'''
  cta2_url_link = '''http://www.india.ford.com/sync'''

[[module]] #Cover 05
path='email_modules/cover/05'
color='''lightblue'''

  title = '''Ford Live Chat'''
  copy = '''Ford Live Chat is now online! Get real-time answers from our team of Ford Advisors between 9am to 8pm. '''
  cta_text = '''START CHATTING'''
  cta_url = '''https://ford-livechat.s3ae.com/in/chat.php?a=1e4b8&intgroup=c3VwcG9ydA__&hg=Pw__&hcgs=MQ__&htgs=MQ__'''
  icon = '''ew'''

[[module]] #Cover 05
path='email_modules/cover/05'
color='''white'''

  title = '''Your Profile Details'''
  copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br>Email&#58; <%${user.CustomAttribute['RealEmail']}%><br>Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br>Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br><br>Anything changed?'''
  cta_text = '''UPDATE YOUR DETAILS'''
  cta_url = '''https://www.india.ford.com/profile-update-form?fbdata=req_firstName=<% ${user['FirstName']} %>||req_lastName=<% ${user['LastName']} %>||req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>||req_EmailID=<% ${user.CustomAttribute['RealEmail']} %>||req_BuildingNo=<% ${user.CustomAttribute['Address_1']} %>||req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>||req_Area=<% ${user.CustomAttribute['Area']} %>||req_Landmark=<% ${user.CustomAttribute['Landmark']} %>||req_city=<% ${user.CustomAttribute['City']} %>||req_State=<% ${user.CustomAttribute['State']} %>||req_postCode=<% ${user.CustomAttribute['Post_Code']} %>'''
  icon = '''ew'''

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