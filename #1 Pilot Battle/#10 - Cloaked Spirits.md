# 10 - Cloaked Spirits

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/10.png)

## My Solution

### Normal

```html
<p a>
<p b>
<style>
	& {
		background: #62306d;
		p {
			top: 0;
			left: 0;
			position: absolute;
		}
		[a] {
			width: 60;
			height: 60;
			border-radius: 50%;
			box-shadow: 74q 163q #e38f66, 74q 163q 0 21q #aa445f, 180q 57q #aa445f, 180q 57q 0 21q #e38f66, 286q 163q #e38f66, 270px 163q 0 21q #aa445f;
		}
		[b] {
			z-index: -1;
			width: 100;
			height: 120;
			color: #f7ec7d;
			box-shadow: 53q 190q, 150px 85q, 150px 190q, 250px 190q;
		}
	}
</style>
```

### Minimal

```html
<p a><p b><style>&{background:#62306D;p{top:0;left:0;position:absolute;}[a]{width:60;height:60;border-radius:50%;box-shadow:74q 163q#E38F66,74q 163q 0 21q#AA445F,180q 57q#AA445F,180q 57q 0 21q#E38F66,286q 163q#E38F66,270px 163q 0 21q#AA445F;}[b]{z-index:-1;width:100;height:120;color:#F7EC7D;box-shadow:53q 190q, 150px 85q,150px 190q,250px 190q;
```

## Score

### 614.93 {345}
