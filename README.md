```js
	//how use

let text = window.text
function handleLeft() {
  text.innerHTML = '=>'
}
function handleRight () {
  text.innerHTML = '<='
}




const OPTIONS = {
  "left": handleLeft,
  "right": handleRight
}

const swipeTrack = new SwipeTrack(OPTIONS)

or 

const swipeTrack = new SwipeTrack({
  "left": handleLeft,
  "right": handleRight,
  
})
```
