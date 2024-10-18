---
layout: page
title: Subscribe
icon: fa fa-users
order: 3
---

Subscribe to receive invitations to upcoming talks, workshops, and conferences. Don't miss out—join our network today and stay informed about the latest in oceanographic research and developments across New Zealand.

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSdvCA3o__WV4_5XPwMzBy-gliWX678RXGbhQbcRBigdTZts3w/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  Email adress:<br>
  <input type="text" name="entry.1182600964" id="entry.1182600964"><br>
  <input type="submit" value="Submit">
</form>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script type="text/javascript">
  $("#gform").on("submit", function(e) {
    $('#gform *').fadeOut(1_000);

    // get all the inputs into a dictionary.
    var $inputs = $('#gform :input');

    // You need to know the id of the element you want to extract
    var values = {};
    $inputs.each(function() {
        values[this.name] = $(this).val();
    });
    console.log(values);
    $('#gform'). prepend('Thank you for your submission ' + values["entry.1182600964"] +'.').fadeIn(500);
    });
</script>
