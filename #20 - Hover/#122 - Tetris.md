# 122 - Tetris

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/122.png)

## My Solution

### Sceenshot
![122 - Tetris](https://i.imgur.com/4k32s0R.jpeg)

### Normal

```html
<ul>
	<a><a><a><a><a r><a>
	<a><a><a><a r><a r><a>
	<a y><a y><a><a r><a><a>
	<a y><a y><a r><a><a v><a>
	<a r><a r><a r><a b><a v><a v>
	<a y><a b><a b><a b><a v><a b>
</ul>

<style>
	* {
		background: #173889;
	}

	p {
		display: grid;
		grid-template-columns: repeat(6, 1fr);
		margin: -8 42;
		gap: 6px;
	}

	a {
		width: 45;
		height: 45;
	}

	[r] {
		background: #ee4f63;
	}
	[b] {
		background: #2ce1ea;
	}
	[y] {
		background: #f8da37;
	}
	[v] {
		background: #b069f7;
	}
</style>
```

### Minimal

```html
<p><a><a><a><a><a r><a><a><a><a><a r><a r><a><a y><a y><a><a r><a><a><a y><a y><a r><a><a v><a><a r><a r><a r><a b><a v><a v><a y><a b><a b><a b><a v><a b><style>*{background:#173889;p{display:grid;grid-template-columns:repeat(6,1fr);margin:-8 42;gap:6px;}a{width:45;height:45;}[r]{background:#EE4F63;}[b]{background:#2CE1EA}[y]{background:#F8DA37}[v]{background:#B069F7
```

## Score

### 611.76{370}
