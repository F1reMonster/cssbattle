# 26 - Smiley

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/26.png)

## My Solution

### Screenshot

![26 - Smiley](https://i.imgur.com/EDET4f5.jpeg)

### Watch video

[![26 - Smiley](https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg)](https://youtu.be/wLsqQuvy8B0)

### Normal

```html
<p></p>
<p a></p>
<p a b></p>
<style>
	& {
		background: #6592cf;
		margin: 176 132;
	}
	p {
		position: fixed;
		width: 80;
		height: 40;
		border-radius: 0 0 90q 90q;
		border: 22q solid#060F55;
		border-top: 0;
	}
	[a] {
		scale: -1;
		top: 24;
		left: 40;
	}
	[b] {
		left: 240;
	}
</style>
```

### Minimal

```html
<p><p a><p a b><style>&{background:#6592CF;margin:176 132}p{position:fixed;width:80;height:40;border-radius:0 0 90q 90q;border:22q solid#060F55;border-top:0}[a]{scale:-1;top:24;left:40}[b]{left:240
```

## Score

### 661.18 {197}
