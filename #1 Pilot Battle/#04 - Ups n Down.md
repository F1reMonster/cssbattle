# 4.Ups n Downs

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/4.png)

## My Solution

### Normal
```html
<p></p>
<p></p>
<p></p>

<style>
	body {
		display: flex;
		padding: 126 42 0;
		background: #62306D;
	}

	p {
		width: 100;
		height: 100;
		border-radius: 0 0 50% 50%;
		background: #F7EC7D;
	}

	p:nth-child(2) {
		transform: scale(-1) translateY(100%);
	}
</style>
```

### Minimal
```html
<p><p><p><style>body{background:#62306D;padding:126 42 0;display:flex;p{width:100;height:100;border-radius:0+0+50%+50%;;background:#F7EC7D;}p:nth-child(2){transform:scale(-1)translateY(100%)
```
## Score
### 666.03{189}