
# Usage

	<div id="fontSelect">
		<span>Arial</span>
		<div class="arrow-down"></div>
		
		<ul>
			<li>Arial,Arial,Helvetica,sans-serif</li>
			<li>Arial Black,Arial Black,Gadget,sans-serif</li>
			<li>Comic Sans MS,Comic Sans MS,cursive</li>
			<li>Courier New,Courier New,Courier,monospace</li>
			<li>Georgia,Georgia,serif</li>
			<li>Impact,Charcoal,sans-serif</li>
			<li>Lucida Console,Monaco,monospace</li>
			<li>Lucida Sans Unicode,Lucida Grande,sans-serif</li>
			<li>Palatino Linotype,Book Antiqua,Palatino,serif</li>
			<li>Tahoma,Geneva,sans-serif</li>
			<li>Times New Roman,Times,serif</li>
			<li>Trebuchet MS,Helvetica,sans-serif</li>
			<li>Verdana,Geneva,sans-serif</li>
			<li>Gill Sans,Geneva,sans-serif</li>
		</ul>
	</div>


To turn the above into a font selector dropdown:

	$('#fontSelect').fontSelector({
		'hide_fallbacks' : true,
		'initial' : 'Courier New,Courier New,Courier,monospace',
		'selected' : function(style) {}
	});


The hide_fallbacks option, when true, prevents the full font stack specified in the ul from being outputted. Instead only the first font name will be shown, the full font stack will be used specified in the css though. The function passed to selected will be called whenever a new font is selected, the first argument is the full font stack. The inital font is the font be initially shown in the dropdown.

# Example

A working demo of the files in the examples folder can be found at:

http://s3.amazonaws.com/jquery-font-chooser/examples/example.html