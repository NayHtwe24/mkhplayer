# MKH Player - jQuery plugin for HTML 5 video and audio

## Usage

```javascript
	$('audio').mkhPlayer();
```

### Sample

	<html>
		<head>
		...
		...
		<link rel="stylesheet" type="text/css" href="css/mkhplayer.default.css"/>
		...
		</head>
		<body>
		...
		...
			<audio id="music3" preload="metadata">
				<source src="media/interlude.mp3">
			</audio>

			<script type="text/javascript" src="https://code.jquery.com/jquery-1.7.1.min.js"></script>
			<script type="text/javascript" src="js/jquery.mkhplayer.js"></script>
			<script type="text/javascript">
				$(document).ready(function(){
					$('audio').mkhPlayer();
				});
			</script>
		</body>
	</html>