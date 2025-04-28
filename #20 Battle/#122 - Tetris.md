# 122.Tetris

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/122.png)

## My Solution

### Normal

```html
<ul>
	<li><li><li><li><li r><li>
	<li><li><li><li r><li r><li>
	<li y><li y><li><li r><li><li>
	<li y><li y><li r><li><li v><li>
	<li r><li r><li r><li b><li v><li v>
	<li y><li b><li b><li b><li v><li b>
</ul>

<style>
	* {
		background: #173889;
	}

	ul,
	li {
		list-style: none;
		padding: 0;
	}

	ul {
		display: grid;
		grid-template-columns: repeat(6, 1fr);
		margin: -8 42;
		gap: 6px;
	}

	li {
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
<ul><li><li><li><li><li r><li><li><li><li><li r><li r><li><li y><li y><li><li r><li><li><li y><li y><li r><li><li v><li><li r><li r><li r><li b><li v><li v><li y><li b><li b><li b><li v><li b></ul><style>*{background: #173889;ul,li{list-style:none;padding:0;}ul{display:grid;grid-template-columns: repeat(6, 1fr);margin:-8 42;gap:6px;}li{width:45;height:45;}[r]{background:#EE4F63;}[b]{background:#2CE1EA}[y]{background:#F8DA37}[v]{background:#B069F7
```

## Score

### 605.49{450}
