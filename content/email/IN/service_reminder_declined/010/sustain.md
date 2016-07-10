+++
markets = [ "in" ]
title = '''IN Service Reminder Declined 010 sustain'''

preheader = '''When you purchase a Ford, you're not just buying a great vehicle - you're joining a family.'''

[[module]]
path='email_modules/header/logo'
color='white'

header_logo_image = '''white'''
header_logo_url = '''https://www.india.ford.com/'''

[[module]]
path='email_modules/cover/06'
color='white'

cover_06_white_copy = '''We noticed that you declined an important part of your servicing at your last appointment. That's got us worried.<br><br>When you come into a Ford service centre, you're putting your vehicle into the best hands possible. Our trained technicians know the specifics of your Ford vehicle and only use genuine Ford parts.<br><br>As part of the Ford family, we've got your back. Visit us at a Ford dealer soon.'''
cover_06_white_cta1_text = '''GET A CALLBACK'''
cover_06_white_cta1_url = '''https://www.india.ford.com/ford-service/service-bookings'''
cover_06_white_cta2_text = '''FIND A DEALER'''
cover_06_white_cta2_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
cover_06_white_icon = '''ew'''
cover_06_white_title = '''Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> needs attention'''

[[module]]
path='email_modules/custom/svcstatus_nocopy'
color='white'

custom_service_status_white_icon1 = '''ew'''
custom_service_status_white_icon2 = '''ew'''
custom_service_status_white_icon3 = '''ew'''
custom_service_status_white_subtitle1 = '''Good to go'''
custom_service_status_white_subtitle2 = '''Good to go'''
custom_service_status_white_subtitle3 = '''Service immediately'''
custom_service_status_white_title1 = '''Brakes'''
custom_service_status_white_title2 = '''Tyres'''
custom_service_status_white_title3 = '''Batteries'''

[[module]]
path='email_modules/split/01'
color='white'

split_01_white_copy = '''Make your Ford Aspire your own, with Ford Genuine Accessories that define your style. From the chrome kit to the rear spoiler - customise your Ford with us.'''
split_01_white_cta_icon = '''play'''
split_01_white_cta_text = '''MAKE IT YOURS!'''
split_01_white_cta_url = '''http://www.india.ford.com/cars/figoaspire/accessories/exterior'''
split_01_white_image = '''tms_20160328'''
split_01_white_title = '''Time to Accessorise'''

[[module]]
path='email_modules/banner/image'
color='white'

image_banner_image1 = '''cashback_20160328'''
image_banner_url1 = '''http://www.google.com'''

[[module]]
path='email_modules/custom/3column_pbsvc'
color='white'

custom_02_white_cta_text = '''FIND A DEALER'''
custom_02_white_cta_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
custom_02_white_text1 = '''We ensure that there are no surprises in your service cost. The price you see online is the price you pay.'''
custom_02_white_text2 = '''Stay home while we pick up, service, and return your vehicle to you. The easiest way to keep your Ford in top shape.'''
custom_02_white_text3 = '''We tell you exactly how much a replacement part will cost before you even visit the service centre.'''
custom_02_white_textlink1_text = '''Check service price'''
custom_02_white_textlink1_url = '''https://www.fordservicepricepromise.com/?extcmp=serca_101115_105328_fordind'''
custom_02_white_textlink2_text = '''Check parts price'''
custom_02_white_textlink2_url = '''https://partscalculator.fordind.com:1443/Fill_Field'''
custom_02_white_title1 = '''Service Price Promise'''
custom_02_white_title2 = '''Pick Up &#38; Drop'''
custom_02_white_title3 = '''Parts Cost Calculator'''

[[module]]
path='email_modules/footer/4icons'
color='white'

footer_in_4icons_icon1_image = '''dealers_20160401'''
footer_in_4icons_icon2_image = '''ford_credit_20160401'''
footer_in_4icons_icon3_image = '''ford_assured_20160401'''
footer_in_4icons_icon4_image = '''customer_care_number_20160401'''

[[module]]
path='email_modules/footer/in/social'
color='white'

[[module]]
path='email_modules/footer/in/online'
color='white'

+++

<%= partial "modules/#{lang}/head" %>

<%= partial "modules/#{lang}/header/logo" %>
<%= partial "modules/#{lang}/cover/06/white" %>
<%= partial "modules/#{lang}/custom/service_status/white"%>
<%= partial "modules/#{lang}/split/01/white" %>
<%= partial "modules/#{lang}/image/banner1", :locals => { :bannerimage => current_page.data.image_banner_image2, :bannerurl => current_page.data.image_banner_url2 }  %>
<%= partial "modules/#{lang}/custom/02/white"%>
<%= partial "modules/#{lang}/footer/in/4icons" %>
<%= partial "modules/#{lang}/footer/in/social" %>
<%= partial "modules/#{lang}/footer/in/online" %>

<%= partial "modules/#{lang}/foot" %>