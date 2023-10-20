## updateState Usage

To update the state of the store, use the `updateState()` function. For example, to update the title property of the store to 'My New Title', you would use the following code:

```javascript
updateState('title', 'My New Title');
```

To retrieve a property from the store, simply access the property on the store object. For example, to retrieve the title property of the store, you would use the following code:

```javascript
const title = store.title;
```


## AddStyle function

The `addStyle` function can be used to add CSS styles to elements on a web page.

### Usage

The `addStyle` function takes two parameters:

* `element`: The element to add the CSS styles to.
* `declaration`: An object of CSS properties and values.

The `declaration` object can contain any valid CSS properties. For example, to add the `background-color: red` style to the `<body>` element, you would use the following code:

```javascript
addStyle(document.body, { backgroundColor: 'red' });
```

To add the `font-size: 16px` style to all of the `.my-elements` elements, you would use the following code:

```javascript
addStyle(document.querySelectorAll('.my-elements'), { fontSize: '16px' });
```
