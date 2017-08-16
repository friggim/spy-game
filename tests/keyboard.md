```javascript
<script>
		window.addEventListener("keypress", dealWithKeyboard, false);
		window.addEventListener("keydown", dealWithKeyboard, false);
		 
		function dealWithKeyboard(e) {
			console.log(e.key);
			if (e.key == 'j'){
				console.log('ok');
			}
		}		
	</script>
  ```
