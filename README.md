# jquery-editable
a jquery plugin to make text editable, support &lt;input>, &lt;select> and &lt;textarea>

## Demo
- http://xiangming.github.io/jquery-editable/

## Basic Usage
Include the latest jQuery library and `jquery.editable.js`

````html
<p class="editable">...</p>
````

```javascript
$('.editable').editable();
```

## options

```javascript
$('.editable').editable({
    action: 'click', //click, dblclick, clickhold
    type: 'input', //input, select, textarea
    className: '', //custom class for editor
    choice: {} //options for select
}, function(e){
    //callback
    console.log(e.value);
});
```

## examples

validation