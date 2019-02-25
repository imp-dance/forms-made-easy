# forms-made-easy
> Forms in HTML by default have next to no use-case design-wise. I'd argue this reset makes more sense on 90% of projects.

* [Demo on CodePen](https://codepen.io/schart/pen/rPyoMp)
* [CDN from impedans.me](https://impedans.me/css/form)

---

### HTML markup

```html
<* class="form">
  <label>Email
    <input type="email" />
  </label>
</*>
```
Leave an empty div to bump into the next column

```html
<label><div></div>
  <button>Login</button>
</label>
```
Add `.onecolumn` to go from two columns to one column with label above the inputs

```html
<* class="form onecolumn">
  <label>Email
    <input type="email" />
  </label>
</*>
```
