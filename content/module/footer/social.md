---
title: Footer social
layout: standard

footer_social_text: Follow us on
footer_social_twitter_url: https://twitter.com
footer_social_facebook_url: https://www.facebook.com

---

<%= partial "modules/#{lang}/head" %>

<p style="text-align: center;">General Version</p>
<%= partial "modules/#{lang}/footer/social" %>
<p style="text-align: center;">AU Version</p>
<%= partial "modules/#{lang}/footer/au/social" %>
<p style="text-align: center;">IN Version</p>
<%= partial "modules/#{lang}/footer/in/social" %>
<p style="text-align: center;">PH Version</p>
<%= partial "modules/#{lang}/footer/ph/social" %>
<p style="text-align: center;">TH Version</p>
<%= partial "modules/#{lang}/footer/th/social" %>
<p style="text-align: center;">VN Version</p>
<%= partial "modules/#{lang}/footer/vn/social" %>

<%= partial "modules/#{lang}/foot" %>