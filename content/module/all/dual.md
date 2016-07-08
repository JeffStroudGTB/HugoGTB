---
title: Dual ALL
layout: standard

module_amount: 4

dual_01_white_icon1: ew
dual_01_white_title1: Dual 01 Title 1
dual_01_white_copy1: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
dual_01_white_icon2: ew
dual_01_white_title2: Dual 01 Title 2
dual_01_white_copy2: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
dual_01_white_cta1_text: Click me!
dual_01_white_cta1_url: http://google.com
dual_01_white_cta2_text: Click me!
dual_01_white_cta2_url: http://google.com

dual_02_white_icon1: ew
dual_02_white_title1: Dual 02 Title 1
dual_02_white_cta1_text: Click Here!
dual_02_white_cta1_url: http://google.com
dual_02_white_cta2_text: Click Here!
dual_02_white_cta2_url: http://google.com
dual_02_white_icon2: ew
dual_02_white_title2: Dual 02 Title 2
dual_02_white_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
dual_02_white_cta3_text: Click Here!
dual_02_white_cta3_url: http://google.com

dual_03_white_title1: Dual 03 Title 1
dual_03_white_cta1a_text: Click me!
dual_03_white_cta1a_url: http://google.com
dual_03_white_cta1b_text: Click me!
dual_03_white_cta1b_url: http://google.com
dual_03_white_icon1: ew
dual_03_white_title2: Dual 03 Title 2
dual_03_white_copy2: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
dual_03_white_cta2a_text: Click me!
dual_03_white_cta2a_url: http://google.com
dual_03_white_cta2b_text: Click me!
dual_03_white_cta2b_url: http://google.com
dual_03_white_icon2: ew

dual_04_white_title1: Dual 04 Title 1
dual_04_white_copy1: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
dual_04_white_cta1a_text: Click me!
dual_04_white_cta1a_url: http://google.com
dual_04_white_cta1b_text: Click me!
dual_04_white_cta1b_url: http://google.com
dual_04_white_cta1c_text: Click me!
dual_04_white_cta1c_url: http://google.com
dual_04_white_icon1: ew
dual_04_white_title2: Dual 04 Title 2
dual_04_white_copy2: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
dual_04_white_cta2a_text: Click me!
dual_04_white_cta2a_url: http://google.com
dual_04_white_cta2b_text: Click me!
dual_04_white_cta2b_url: http://google.com
dual_04_white_cta2c_text: Click me!
dual_04_white_cta2c_url: http://google.com
dual_04_white_icon2: ew

---
<%= partial "modules/#{lang}/modifiedhead" %>

  <ul>
    <p style="color:#000001; text-decoration:none;">Go To</p>
    <% 1.upto(current_page.data.module_amount.to_f) do |num| %>
      <li><a href="#0<%= num %>">Dual <%= num %></a></li>
    <% end %>
  </ul>

<% 1.upto(current_page.data.module_amount.to_f) do |num| %>
  <p id="0<%= num %>" style="text-align:center;text-decoration:underline;color:#3366BB"><%= link_to "Dual 0" + num.to_s, "htm/modules/dual/0" + num.to_s + ".html" %></p>
<%= partial "modules/#{lang}/dual/0" + num.to_s + "/white" %>
  <% end %>

<%= partial "modules/#{lang}/foot" %>