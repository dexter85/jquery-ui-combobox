jquery-ui-combobox
==================

Fast Combobox for Jquery ui

How to usage:
1) Include jquery, jquery-ui, jquery-ui-combobox;
2) bind combobox in your select, example:
<code>


  <script type="text/javascript">
  $(document).ready(function() {
    $("#foo").combobox(
		{
      selected: function(event, ui) 
			{
        // Event Selected
			},
  			maxResult: 10,
  			minLength: 2,
			}); 
    }
  });
  </script>


  <select id="foo">
    ......
  </select>

</code>
3) if you need change select value 
<code>
  $("#foo").combobox("value", myvalue);
</code>

4) if you need destroy 
<code>
  $("#foo").combobox("destory");
</code>

