<p align="center">
  <img src="icons/icon256.png" alt=""/>
  <h3 align="center">Hex Picker</h3> 
</p>
<p align="center">A simple and easy-to-use color picker for your project.</p>
<p align="center"> </p>

<br>
<br>


## Installation 
[Click here](https://chrome.google.com/webstore/detail/hex-picker/jmnkgndafoldkblpnmmollbgkdfemmfc) to add the extension to your browser.

## Usage

```javascript
Copy codeimport ColorPicker from 'color-picker';

const picker = new ColorPicker();
picker.show();
```

## Methods

```javascript
Copy code// Show the color picker
picker.show();

// Hide the color picker
picker.hide();

// Get the current color
const color = picker.getColor();

// Set the current color
picker.setColor('#ff0000');
```

## Browser Support

Color Picker works in modern browsers that support the HTML5 `<input type="color">` element.

## Licensing

Color Picker is released under the MIT license.

## Contributing

We welcome any contributions to Color Picker. Feel free to submit a pull request or create an issue for any bugs or feature requests.
