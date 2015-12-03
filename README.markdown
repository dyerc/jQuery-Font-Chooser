# Demo

A working demo of the files in the examples folder can be found at:
http://s3.amazonaws.com/jquery-font-chooser/examples/example.html

# Usage

	<div id="fontSelect" class="fontSelect">
		<div class="arrow-down"></div>
	</div>


To turn the above into a font selector dropdown:

	$('#fontSelect').fontSelector({
			'hide_fallbacks' : true,
			'initial' : 'Courier New,Courier New,Courier,monospace',
			'selected' : function(style) { alert(style); },
			'opened' : function(style) { alert('opened'); },
			'closed' : function(style) { alert('closed'); },
			'fonts' : [
				'Arial,Arial,Helvetica,sans-serif',
				'Arial Black,Arial Black,Gadget,sans-serif',
				'Comic Sans MS,Comic Sans MS,cursive',
				'Courier New,Courier New,Courier,monospace',
				'Georgia,Georgia,serif',
				'Impact,Charcoal,sans-serif',
				'Lucida Console,Monaco,monospace',
				'Lucida Sans Unicode,Lucida Grande,sans-serif',
				'Palatino Linotype,Book Antiqua,Palatino,serif',
				'Tahoma,Geneva,sans-serif',
				'Times New Roman,Times,serif',
				'Trebuchet MS,Helvetica,sans-serif',
				'Verdana,Geneva,sans-serif',
				'Gill Sans,Geneva,sans-serif'
				]
		});


The hide_fallbacks option, when true, prevents the full font stack specified in the ul from being outputted. Instead only the first font name will be shown, the full font stack will be used specified in the css though. The function passed to selected will be called whenever a new font is selected, the first argument is the full font stack. The inital font is the font be initially shown in the dropdown.

