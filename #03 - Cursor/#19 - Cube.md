# 19 - Cube

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/19.png)

## My Solution

### Sceenshot

![19 - Cube](https://i.imgur.com/QjOCgnL.jpeg)

### Normal

```html
<style>
	& {
		background: #0b2429;
		margin: 37 122;
	}
	& > * {
		height: 210;
		width: 140;
		background: conic-gradient(at 50%33%, #1a4341 135deg, #f3ac3c 135deg, #f3ac3c 225deg, #998235 180deg);
		clip-path: polygon(50% 0, 100% 33%, 100% 67%, 50% 100%, 0 67%, 0 33%);
	}
</style>
```

### Minimal

```html
<style>&{background:#0b2429;margin:37 122;>*{height:210;width:140;background:conic-gradient(at 50%33%,#1a4341 135deg,#f3ac3c 135deg,#f3ac3c 225deg,#998235 180deg);clip-path:polygon(50%0,100%33%,100%67%,50%100%,0 67%,0 33%
```

## Score

### 648.67 {221}
