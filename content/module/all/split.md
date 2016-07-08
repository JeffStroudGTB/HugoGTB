---
title: Split ALL
layout: standard

module_amount: 12

split_01_black_title: Split 01 Title
split_01_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
split_01_black_cta_text: Click me!
split_01_black_cta_url: http://google.com
split_01_black_cta_icon: play
split_01_black_image: tms_20160328

split_02_black_title: Split 02 Title
split_02_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
split_02_black_cta_text: Click me!
split_02_black_cta_url: http://google.com
split_02_black_cta_icon: play
split_02_black_image: tms_20160328

split_03_black_title: Split 03 Title
split_03_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
split_03_black_cta_text: Click me!
split_03_black_cta_url: http://google.com
split_03_black_cta_icon: play
split_03_black_image: tms_20160328

split_04_black_title: Split 04 Title
split_04_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
split_04_black_cta_text: Click me!
split_04_black_cta_url: http://google.com
split_04_black_cta_icon: play
split_04_black_image: tms_20160328

split_05_black_title: Split 05 Title
split_05_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
split_05_black_cta1_text: Click me!
split_05_black_cta1_url: http://google.com
split_05_black_cta2_text: Click me!
split_05_black_cta2_url: http://google.com
split_05_black_cta_icon: play
split_05_black_image: tms_20160328

split_06_black_title: Split 06 Title
split_06_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
split_06_black_cta1_text: Click me!
split_06_black_cta1_url: http://google.com
split_06_black_cta2_text: Click me!
split_06_black_cta2_url: http://google.com
split_06_black_cta_icon: play
split_06_black_image: tms_20160328

split_07_black_title: Split 07 Title
split_07_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
split_07_black_cta1_text: Click me!
split_07_black_cta1_url: http://google.com
split_07_black_cta2_text: Click me!
split_07_black_cta2_url: http://google.com
split_07_black_cta_icon: play
split_07_black_image: tms_20160328

split_08_black_title: Split 08 Title
split_08_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
split_08_black_cta1_text: Click me!
split_08_black_cta1_url: http://google.com
split_08_black_cta2_text: Click me!
split_08_black_cta2_url: http://google.com
split_08_black_cta_icon: play
split_08_black_image: tms_20160328

split_09_black_title: Split 09 Title
split_09_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
split_09_black_cta_text: Click me!
split_09_black_cta_url: http://google.com
split_09_black_image: tms_20160328

split_10_black_title: Split 10 Title
split_10_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
split_10_black_cta_text: Click me!
split_10_black_cta_url: http://google.com
split_10_black_image: tms_20160328

split_11_black_title: Split 11 Title
split_11_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
split_11_black_cta_text: Click me!
split_11_black_cta_url: http://google.com
split_11_black_image: tms_20160328

split_12_black_title: Split 12 Title
split_12_black_copy: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
split_12_black_cta_text: Click me!
split_12_black_cta_url: http://google.com
split_12_black_image: tms_20160328

---

<%= partial "modules/#{lang}/modifiedhead" %>

<div class="sidebar">
  <ul>
    <p style="color:#000001; text-decoration:none;">Go To</p>
    <% 1.upto(9) do |num| %>
      <li><a href="#0<%= num %>">Split <%= num %></a></li>
    <% end %>
    <% 10.upto(current_page.data.module_amount.to_f) do |num| %>
      <li><a href="#<%= num %>">Split <%= num %></a></li>
    <% end %>
  </ul>
</div>


<% 1.upto(9) do |num| %>
  <p id="0<%= num %>" style="text-align:center;text-decoration:underline;color:#3366BB"><%= link_to "Split 0" + num.to_s, "htm/modules/split/0" + num.to_s + ".html" %></p>
  <%= partial "modules/#{lang}/split/0" + num.to_s + "/black" %>
  <% end %>

<% 10.upto(current_page.data.module_amount.to_f) do |num| %>
  <p id="<%= num %>" style="text-align:center;text-decoration:underline;color:#3366BB"><%= link_to "Split " + num.to_s, "htm/modules/split/" + num.to_s + ".html" %></p>
  <%= partial "modules/#{lang}/split/" + num.to_s + "/black" %>
  <% end %>

<%= partial "modules/#{lang}/foot" %>