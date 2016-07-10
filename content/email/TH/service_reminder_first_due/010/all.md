+++
markets = ["th"]
title = '''TH Service Reminder First Due 010 All'''

preheader = '''ฟอร์ดขอแจ้งให้คุณทราบว่า รถคันใหม่ของคุณ ถึงกำหนดตรวจเช็คระยะครั้งแรกแล้ว เนื่องจากรถใหม่ทุกคัน จะมีระยะในการปรับสภาพ การทำงานของรถ'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  header_logo_image = '''white'''
  header_logo_url = '''http://www.ford.co.th'''

[[module]] #Cover 06
path='email_modules/cover/06'
color='''black'''

  cover_06_white_title = '''White Title'''
  cover_06_white_copy = '''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<br><br>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum'''
  cover_06_white_cta1_text = '''Click me!'''
  cover_06_white_cta1_url = '''http://google.com'''
  cover_06_white_cta2_text = '''Click me long time!'''
  cover_06_white_cta2_url = '''http://google.com'''
  cover_06_white_icon = '''ew'''

[[module]] #Custom 01
path='email_modules/custom/01'
color='black'

  custom_01_white_title = '''ทำไมต้องศูนย์บริการฟอร์ด?'''
  custom_01_white_icon1 = '''ico_2e_fordsvc_a'''
  custom_01_white_text1 = '''มั่นใจอะไหล่แท้ฟอร์ด&#65279;100%&#65279;พร้อมการบำรุงรักษารถยนต์&#65279;อย่างมีประสิทธิภาพเพื่อ&#65279;สมรรถนะสูงสุดของรถคุณ'''
  custom_01_white_icon2 = '''ico_2e_fordsvc_b'''
  custom_01_white_text2 = '''ตรวจเช็คด้วยช่างเทคนิค&#65279;ฟอร์ดที่ผ่านการอบรม&#65279;รวมถึงเครื่องมือและอุปกรณ์&#65279;ทันสมัยที่ออกแบบมาเพื่อ&#65279;รถฟอร์ดโดยเฉพาะ '''
  custom_01_white_icon3 = '''ico_2e_fordsvc_c_th'''
  custom_01_white_text3 = '''เก็บบันทึกสถิติรถฟอร์ด&#65279;ของคุณอย่างเป็นระบบ&#65279;เพื่อเพิ่มมูลค่าในการขายต่อ'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image_banner_image = '''cashback_20160328'''
  image_banner_url = ''''''

[[module]] #Split 04
path='email_modules/split/04'
color='black'

  split_04_green_title = '''ประหยัดกับชุดน้ำมันเครื่องสุดคุ้ม'''
  split_04_green_copy = '''ฟอร์ดใจดีมอบส่วนลดมูลค่า 300 บาท เมื่อซื้อโปรแกรมชุดน้ำมันเครื่องสุดคุ้ม แพ็คเกจใดก็ได้ ซื้อวันนี้ประหยัดทันที'''
  split_04_green_cta_text = '''คลิกเพื่อดูรายละเอียดและราคา'''
  split_04_green_cta_url = '''http://www.ford.co.th/buying/solutions/oilsavepack'''
  split_04_green_cta_icon = '''more'''
  split_04_green_image = '''tms_20160328'''

[[module]] #Split 03
path='email_modules/split/03'
color='black'

  split_03_white_title = '''ส่วนลด 10%<br/>โปรแกรม SSP'''
  split_03_white_copy = '''รับส่วนลดเพิ่ม 10% สูงสุดถึง 3,700 บาท เมื่อซื้อโปรแกรมบำรุงรักษารถยนต์ตามระยะ SSP พร้อมผ่อน 0% นาน 10 เดือน ด้วยบัตรเครดิตกสิกรไทย'''
  split_03_white_cta_text = '''เริ่มต้นการประหยัด'''
  split_03_white_cta_url = '''http://www.ford.co.th/buying/solutions/schedule-service'''
  split_03_white_cta_icon = '''more'''
  split_03_white_image = '''tms_20160328'''

[[module]] #Dual 03
path='email_modules/dual/03'
color='white'

  dual_03_white_title1 = '''นัดหมายเข้ารับบริการ'''
  dual_03_white_cta1a_text = '''ติดต่อ<%${user.CustomAttribute['Sales_Dealer']}%><br/>ได้ที่ <% ${user.CustomAttribute['Dealer_Phone']} %>'''
  dual_03_white_cta1a_url = '''tel:<% ${user.CustomAttribute['Dealer_Phone']} %>'''
  dual_03_white_cta1b_text = '''ค้นหาตัวแทนจำหน่ายใกล้บ้าน<br/>คุณ'''
  dual_03_white_cta1b_url = '''http://www.ford.co.th/locate-a-dealer/'''
  dual_03_white_icon1 = '''ew'''
  dual_03_white_title2 = '''ศูนย์ข้อมูลเจ้าของรถ'''
  dual_03_white_copy2 = '''ทุกความช่วยเหลือที่คุณต้องการง่ายๆ&#65279;ในที่เดียว&#65279;สำหรับเจ้าของรถฟอร์ดเท่านั้น'''
  dual_03_white_cta2a_text = '''วิดีโอสาธิตวิธีการใช้งาน&#65279;คุณสมบัติต่างๆ'''
  dual_03_white_cta2a_url = '''https://www.ford.co.th/owner'''
  dual_03_white_cta2b_text = '''ผลิตภัณฑ์และบริการของฟอร์ด'''
  dual_03_white_cta2b_url = '''https://www.ford.co.th/owner'''
  dual_03_white_icon2 = '''ew'''

+++