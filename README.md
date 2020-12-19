# CSS Media Query


### Device = Desktops
### Screen = 1281px to higher resolution desktops

```css
@media (min-width: 1281px) {
  // CSS
}
```
<hr>

### Device = Laptops, Desktops
### Screen = B/w 1025px to 1280px

```css
@media (min-width: 1025px) and (max-width: 1280px) {
  // CSS
}
```
<hr>

### Device = Tablets, Ipads (portrait)
### Screen = B/w 768px to 1024px

```css
@media (min-width: 768px) and (max-width: 1024px) {
  // CSS
}
```
<hr>

### Device = Tablets, Ipads (landscape)
### Screen = B/w 768px to 1024px

```css
@media (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
  // CSS
}
```
<hr>
 
### Device = Low Resolution Tablets, Mobiles (Landscape)
### Screen = B/w 481px to 767px

```css
@media (min-width: 481px) and (max-width: 767px) {
  // CSS
}
```
<hr>

### Device = Most of the Smartphones Mobiles (Portrait)
### Screen = B/w 320px to 479px

```css
@media (min-width: 320px) and (max-width: 480px) {
  // CSS
}
```