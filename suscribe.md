---
layout: page
title: Suscribe
weight : 98
---

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSdvCA3o__WV4_5XPwMzBy-gliWX678RXGbhQbcRBigdTZts3w/formResponse?usp=pp_url&entry.1182600964=oceanography@newzeland.com" target="hidden_iframe" onsubmit="submitted=true;">
  Email adress:<br>
  <input type="text" name="entry.1182600964" id="entry.1182600964"><br>
  <input type="submit" value="Submit">
</form>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="{{ site.baseurl }}/_js/jquery.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed...');
  });
</script>