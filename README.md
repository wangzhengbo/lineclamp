# .lineclamp

> text-overflow: ellipsis with multiple lines.

```css
.lineclamp {
  line-height: 1.25; /* required */
  height: 2.5em; /* required */
  background-color: #fff; /* required */
  position: relative;
  padding-right: 1em;
  overflow: hidden;
}

.lineclamp:before {
  content: "...";
  position: absolute;
  right: 0;
  bottom: 0;
  display: inline-block;
  width: 1em;
}

.lineclamp:after {
  content: "";
  position: relative;
  right: -1em;
  float: right;
  width: 1em;
  height: 100%;
  background-color: inherit;
}
```

## Test

See the [result](http://byodkm.github.io/lineclamp/test/).
