+++
moduletypes = [ "All" ]
title = 'IN Anniversary 010 All'

preheader='''preheader goes here'''

[[module]]
path='email_modules/header/logo'
color='white'

image='''white'''
url='''https://www.india.ford.com/'''

[[module]]
path='email_modules/image/banner'
color='white'

image='''cashback_20160328'''
url='''www.google.com'''

[[module]]
path='email_modules/cover/10'
color='white'

title='''How are you celebrating?'''
copy='''Hello <%${user.CustomAttribute['FullName']}%><br/><br/>It has been nearly one year for you and your Ford <%${user.CustomAttribute['Selected_Vehicle']}%>! We sincerely hope the drive has been smooth, rewarding, and - most of all - enjoyable.<br/><br/>As part of the Ford family, we'll continue to look out for you this coming year. That's why we created the Ford Owners app - to make owning a Ford easier than ever.'''

[[module]]
path='email_modules/custom/05'
color='white'

title1='''Service Checklist'''
icon1='''ew'''
text1='''Know what needs to be serviced, when.'''
title2='''24h Roadside Assistance'''
icon2='''ew'''
text2='''Because we'll never leave you stranded.'''
title3='''How-to Videos'''
icon3='''ew'''
text3='''Step-by-step guide to Ford tech. '''
title4='''Dealer Locator'''
icon4='''ew'''
text4='''Because we're always here for you.'''

[[module]]
path='email_modules/cover/12'
color='white'

copy='''Download the app now, absolutely free, and have all of this important information and more at your fingertips, anywhere you and your Ford go.'''
cta1_text='''iOS'''
cta1_url='''https://itunes.apple.com/in/app/ford-owners/id990342351?mt=8'''
cta2_text='''ANDROID'''
cta2_url='''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en'''

[[module]]
path='email_modules/cover/05'
color='white'

title='''Your Profile Details'''
copy='''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br>Email&#58; <%${user.CustomAttribute['RealEmail']}%><br>Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br>Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br><br>Anything changed?'''
cta_text='''UPDATED YOUR DETAILS'''
cta_url='''https://www.india.ford.com/profile-update-form?fbdata=req_firstName=<% ${user['FirstName']} %>||req_lastName=<% ${user['LastName']} %>||req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>||req_EmailID=<% ${user.CustomAttribute['RealEmail']} %>||req_BuildingNo=<% ${user.CustomAttribute['Address_1']} %>||req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>||req_Area=<% ${user.CustomAttribute['Area']} %>||req_Landmark=<% ${user.CustomAttribute['Landmark']} %>||req_city=<% ${user.CustomAttribute['City']} %>||req_State=<% ${user.CustomAttribute['State']} %>||req_postCode=<% ${user.CustomAttribute['Post_Code']} %>'''
icon='''ew'''

[[module]]
path='email_modules/footer/5icons'
color='white'

icon1_image='''dealers_20160401'''
icon1_url='''http://google.com'''
icon2_image='''ford_credit_20160401'''
icon2_url='''http://google.com'''
icon3_image='''ford_assured_20160401'''
icon3_url='''http://google.com'''
icon4_image='''customer_care_number_20160401'''
icon4_url='''http://google.com'''
icon5_image='''rsa_no_20160401'''
icon5_url='''http://google.com'''

[[module]]
path='email_modules/footer/in/social'
color='white'

[[module]]
path='email_modules/footer/in/online'
color='white'
+++

<%= partial "modules/#{lang}/head" %>

<%= partial "modules/#{lang}/header/logo" %>
<%= partial "modules/#{lang}/image/banner" %>
<%= partial "modules/#{lang}/cover/10/white" %>
<%= partial "modules/#{lang}/custom/05/white" %>
<%= partial "modules/#{lang}/cover/12/white" %>
<%= partial "modules/#{lang}/cover/05/white" %>
<%= partial "modules/#{lang}/footer/in/5icons" %>
<%= partial "modules/#{lang}/footer/in/social" %>
<%= partial "modules/#{lang}/footer/in/online" %>

<%= partial "modules/#{lang}/foot" %>