# 12 - Wiggly Moustache

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/12.png)

## My Solution

### Normal

```html
<a>
<a a>
<a b>
<p>
<style>
	& {
		background: #f5d6b4;
		margin: 142 62;
	}
	p {
		width: 20;
		height: 20;
		border-radius: 50%;
		color: #d86f45;
		box-shadow: -170q -27q, 85q -27q;
	}
	a {
		float: left;
		width: 100;
		height: 50;
		border-radius: 0 0 80q 80q;
		background: radial-gradient(at 50% 0, #0000 30px, #d86f45 0);
	}
	[a] {
		margin: -50 -20;
		scale: -1;
	}
	[b] {
		translate: 64q;
	}
</style>
```

### Minimal

```html
<a><a a><a b><p><style>&{background:#F5D6B4;margin:142 62}p{width:20;height:20;border-radius: 50%;color:D86F45;box-shadow:-170q -27q,85q -27q}a{float:left;width:100;height:50;border-radius: 0 0 80q 80q;background:radial-gradient(at 50% 0,#0000 30px,#D86F45 0)}[a]{margin:-50 -20;scale:-1} [b]{translate:64q
```

## Score

### 620.64 {311}
