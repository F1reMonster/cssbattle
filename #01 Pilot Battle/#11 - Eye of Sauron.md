# 11 - Eye of Sauron

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/11.png)

## My Solution

### Normal

```html
<p a>
<p b>
<p c>
<style>
  & {
    background:#191210;
    p {
      position: absolute;
      border-radius: 50%;
    }
    [a], [c] {
      width: 60;
      height: 60;
      border-width: 22q;
      border-style: solid;
      border-color: #191210 #191210 #ECA03D #ECA03D;
    }
    [a] {
      top: 84;
      left: 50;
      rotate: -45deg;     
    }
    [c] {
      top: 84;
      right: 50;
      rotate: 135deg;
    }
    [b] {
      z-index: 2;
      width: 140;
      height: 140;
      top: 64;
      left: 130;
      background: radial-gradient(circle, #84271C 26q, #191210 26q, #191210 53q, #ECA03D 53q);
    }
  }
</style>

```

### Minimal

```html
<p a><p b><p c><style>&{background:#191210;p{position:absolute;border-radius:50%;}[a],[c]{width:60;height:60;border-width:22q;border-style:solid;border-color:#191210#191210#ECA03D#ECA03D;}[a]{top:84;left:50;rotate:-45deg;}[c]{top:84;right:50;rotate:135deg;}[b]{z-index:2;width:140;height:140;top:64;left:130;background:radial-gradient(circle,#84271C 26q,#191210 26q,#191210 53q,#ECA03D 53q)

```

## Score

### 609.72 {390}
