# Air Chars
Animate typed characters in a Input. Demo: https://codepen.io/JoyZi/pen/BZaPMe

### Settings

Option | Type | Default 
------ | ---- | ------- 
duration | number | 1 
upperLimit | number | 150
sizeInterval | array | [15, 80] 

### [Demo](https://codepen.io/JoyZi/pen/BZaPMe)

### Инициализация после подключения самого плагина

```javascript
$( document ).ready( function () {
    $( "input" ).airChars( {
        duration: 0.8,
        upperLimit: 200,
        sizeInterval: [ 15, 80 ]
    } );
} );
```
