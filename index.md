---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---


- ここらへんに適当にすればいいんじゃろうが
- おそらく

## h2

### h3?

<script type="text/javascript" src="js/libs/jquery/jquery-1.10.1.min.js"></script>
<script>
$(function() {
  $("*").contents().filter(function() {
    return this.nodeType==8;
  }).each(function(i, e) {
    var tooltips = e.nodeValue.replace(/^ *[\n\r]|[\n\r]$/g, '');
    $(this).next().attr('title', tooltips);
  });
});
</script>

### h3
こっちにも書かないとScript挿入できたか分からないよ！