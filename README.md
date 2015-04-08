# font-awesome-rtl

Make font-awesome play nicely on right-to-left websites

[Demo](https://fisharebest.github.io/font-awesome-rtl)

# How to use

1. Load font-awesome.css
2. Load font-awesome-rtl.css
3. Add `dir="rtl"` to a suitable parent, such as `<html dir="rtl">`

# What is supported

## Reversible glyphs are reversed:

```html
<i class="fa fa-bullhorn"></i> points left-to-right
<i class="fa fa-star-half"></i> left half of a star
<div dir="rtl">
	<i class="fa fa-bullhorn"></i> points right-to-left
	<i class="fa fa-star-half"></i> right half of a star
</div>
```

## List icons appear in the correct place

```html
<ul class="fa-ul">
	<li><i class="fa-li fa fa-check-square"></i> Check!
	<li><i class="fa-li fa fa-spinner fa-spin"></i> Spins clockwise
</ul>
<div dir="rtl">
	<ul class="fa-ul">
		<li><i class="fa-li fa fa-check-square"></i> Check!
		<li><i class="fa-li fa fa-spinner fa-spin"></i> Spins anti-clockwise
	</ul>
</div>
```

## Start and end versions of all left and right arrows

```html
<i class="fa fa-chevron-right"></i> points left-to-right
<i class="fa fa-chevron-left"></i> points right-to-left
<i class="fa fa-chevron-end"></i> points left-to-right
<i class="fa fa-chevron-start"></i> points right-to-left
<div dir="rtl">
	<i class="fa fa-chevron-right"></i> points left-to-right
	<i class="fa fa-chevron-left"></i> points right-to-left
	<i class="fa fa-chevron-end"></i> points right-to-left
	<i class="fa fa-chevron-start"></i> points left-to-right
</div>
```
