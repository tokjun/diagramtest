
# diagramtest

You can manually parse the text:
<div id="diagram"></div>
<script>
  var diagram = Diagram.parse("A->B: Message");
  diagram.drawSVG("diagram", {theme: 'hand'});
</script>
