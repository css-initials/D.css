# D.css
CSS Transform library.

## Usage
````html
<head>
  <link rel="stylesheet" href="D.css">
</head>
````

### Ex.

#### @cube-0
````html
<div data-D="@cube-0_wireframe @x-down+ @y-down++">
  BOX<br>
  BOX<br>
  BOX<br>
  BOX<br>
</div>
````
![@cube-0](http://css-initials.com/s/D_ex1.png)

#### @cube-1
````html
<div data-D="@cube-1_wireframe @x-down+ @y-down++">
  AAAA
  <div>BBBB</div>
</div>
````
![@cube-1](http://css-initials.com/s/D_ex2.png)

#### @cube-2
````html
<div data-D="@cube-2_wireframe @x-down+ @y-down++" style="width: 100px; height: 100px;">
  <div>AAAA</div>
  <div>BBBB</div>
</div>
````
![@cube-2](http://css-initials.com/s/D_ex3.png)

#### Mixed
+ data-L: <http://layout.css-initials.com>
+ data-A: <http://animation.css-initials.com>
````html
<div data-D="@cube-2_wireframe @x-down+ @y-down++" data-L="@h-1 @w-1" data-A="@rotate-y">
  <div>AAAA</div>
  <div>BBBB</div>
</div>
````
![mixed ex1](http://css-initials.com/s/D_anim_ex1.gif)
````html
<div data-D="@cube-2_wireframe-w_shader-b @x-down+ @y-down++" data-L="@h-2 @w-1" data-A="@rotate-y @rotate-x">
  <div>AAAA</div>
  <div>BBBB</div>
</div>
````
![mixed ex2](http://css-initials.com/s/D_anim_ex2.gif)

## Reference
<http://dimension.css-initials.com>

| Keyword |
|---------|
| [@X @Y @Z](http://dimension.css-initials.com/xyz/)   |
| [@cube](http://animation.css-initials.com/slide/)  |

| Global modifier |
|-----------------|
| [_wireframe](http://animation.css-initials.com/modifier/#_delay) |
| [_shader](http://animation.css-initials.com/modifier/#_repeat) |
| [_depth](http://animation.css-initials.com/modifier/#_alternate) |


## Licence
MIT
