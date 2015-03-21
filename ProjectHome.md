Ligature.js will go through the text on a web-page, and insert ligatures where appropriate.

To use Ligature.js, simply call the ligature function when a page is loaded:

```
<body onload="ligature();">
...
```

Or, using jQuery:

```
<script type="text/javascript">
    $(function() {
        ligature();
    });
</script>
```

To enable extended (slightly more pretentious) ligatures, pass `true` as the first argument:

```
ligature(true);
```

To apply ligature insertion to only a specific part of the page, pass a context as the second argument:

```
ligature(false, document.getElementById('myMemoirs'));
```

For best results, use a serif font. Enjoy.