# 28 - Cups & Balls

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/28.png)

## My Solution

### Screenshot

![28 - Cups & Balls](https://i.imgur.com/siRRShq.jpeg)

### Normal

```html
<p></p>
<p b></p>
<p c></p>
<p d></p>
<p b e></p>
<p></p>
<p d></p>
<p c f></p>
<style>
	& {
		margin: 72 52;
		background: #1a4341;
	}
	p {
		float: left;
		margin: 10;
		width: 50;
		height: 50;
		border-radius: 2in;
		background: #998235;
	}
	[b],
	[d] {
		background: #f3ac3c;
	}
	[b],
	[c] {
		border-radius: 2in 2in 0 0;
	}
	[e],
	[f] {
		scale: -1;
	}
</style>
```

### Minimal

```html
<p><p b><p c><p d><p b e><p><p d><p c f><style>&{margin:72 52;background:#1A4341}p{float:left;margin:10;width:50;height:50;border-radius:2in;background:#998235}[b],[d]{background:#F3AC3C}[b],[c]{border-radius:2in 2in 0 0}[e],[f]{scale:-1
```

## Score

### 641.79 {237}
