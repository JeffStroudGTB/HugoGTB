+++
markets = [ "in" ]
title = '''IN Enews 010 All'''

preheader = '''preheader goes here'''

[[module]]
path='email_modules/header/logo'
color='white'

image = '''white'''
url = '''http://google.com'''

[[module]]
path='email_modules/cover/06'
color='white'

copy = '''Hello <%${user.CustomAttribute['FullName']}%><br><br>Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%>'s warranty will expire on <%${user.CustomAttribute['EWDate']}%>. Knowing you and your Ford are protected means the world to us, so we'd like to offer you an opportunity to extend your vehicle's warranty.<br><br>Our Extended Warranty Plans are designed specifically for your vehicle, and protect you from out-of-pocket bills. They cover major mechanical and electric failures, and are even transferrable - improving your vehicle's resale value.<br><br>We've got your back. Get in touch today and stay protected.'''
cta1_text = '''STAY COVERED'''
cta1_url = '''www.india.ford.com/ford-service/solutions/extended-warranty'''
cta2_text = '''GET A CALLBACK'''
cta2_url = '''www.india.ford.com/callback/confirmation'''
icon = '''ew'''
title = '''Let's keep a good thing going'''

[[module]]
path='email_modules/image/banner'
color='nothing'

image = '''cashback_20160328'''
url = '''http://www.google.com'''

[[module]]
path='email_modules/footer/5icons'
color='nothing'

icon1_image = '''dealers_20160401'''
icon1_url = '''url.com'''
alt1 = '''altname'''
icon2_image = '''ford_credit_20160401'''
icon2_url = '''url.com'''
alt2 = '''altname'''
icon3_image = '''ford_assured_20160401'''
icon3_url = '''url.com'''
alt3 = '''altname'''
icon4_image = '''customer_care_number_20160401'''
icon4_url = '''url.com'''
alt4 = '''altname'''
icon5_image = '''rsa_no_20160401'''
icon5_url = '''url.com'''
alt5 = '''altname'''

[[module]]
path='email_modules/footer/in/social'
color='nothing'

[[module]]
path='email_modules/footer/in/online'
color='nothing'

+++

<%= partial '''modules/#{lang}/head''' %>

<%= partial '''modules/#{lang}/header/logo''' %>
<%= partial '''modules/#{lang}/cover/06/white''' %>
<%= partial '''modules/#{lang}/image/banner''' %>  
<%= partial '''modules/#{lang}/footer/in/5icons''' %>
<%= partial '''modules/#{lang}/footer/in/social''' %>
<%= partial '''modules/#{lang}/footer/in/online''' %>

<%= partial '''modules/#{lang}/foot''' %>