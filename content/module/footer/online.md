---
title: Footer Online
layout: standard

footer_online_text: copy goes here

---

<%= partial "modules/#{lang}/head" %>

<p style="text-align: center;">General Version</p>
<%= partial "modules/#{lang}/footer/online" %>
<p style="text-align: center;">AU Version</p>
<%= partial "modules/#{lang}/footer/au/online" %>
<p style="text-align: center;">IN Version</p>
<%= partial "modules/#{lang}/footer/in/online" %>
<p style="text-align: center;">PH Version</p>
<%= partial "modules/#{lang}/footer/ph/online" %>
<p style="text-align: center;">TH Version</p>
<%= partial "modules/#{lang}/footer/th/online" %>
<p style="text-align: center;">VN Version</p>
<%= partial "modules/#{lang}/footer/vn/online" %>

<%= partial "modules/#{lang}/foot" %>