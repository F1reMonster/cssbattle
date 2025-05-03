# 14 - Web Maker Logo

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/14.png)

## My Solution

### Sceenshot

![14 - Web Maker Logo](https://i.imgur.com/FlTIDW5.jpeg)

## Normal

```html
<p a></p>
<p b></p>

<style>
	& {
		background: #f2f2b6;
		margin: 61 52;
		--a: #fd4602;
	}
	p {
		float: left;
		border-width: 130 75;
		width: 0;
		border-style: solid;
		filter: drop-shadow(20px 0px var(--a));
	}
	[a] {
		border-color: #ff6d00 #0000 #0000;
	}
	[b] {
		--a: #ff6d00;
		transform: translate(110px, -422px);
		border-color: #0000 #0000 #fd4602;
	}
</style>
```

### Minimal

```html
<p a><p b><style>&{background:#F2F2B6;margin:61 52;--a:#FD4602;}p{float:left;border-width:130 75;width:0;border-style:solid;filter:drop-shadow(20px 0px var(--a));}[a]{border-color:FF6D00#0000#0000;}[b]{--a:#FF6D00;transform:translate(110px,-422px);border-color:#0000#0000#FD4602;
```

## Score

### 628 {279}
