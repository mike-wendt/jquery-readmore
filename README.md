
##What

Display on a certain number of characters of text, and trigger the display of the full text with an automatically appended "Read More" link.

Customizable: number of characters, ... ellipses text, and "read more" link

##How

Import the script, then on an element that has just child text, apply a selector that you can find with jQuery and call the plugin

```
<div class="nachooooo">
  Mucho text here
</div>

<script>
  $('.nachooooo').readmore();
</script>

```