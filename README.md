# FlashyJS 🌟

![FlashyJS](https://img.shields.io/badge/FlashyJS-v1.0.0-brightgreen)

Welcome to **FlashyJS**, a lightweight and modern library for displaying notifications on the web. This repository provides an easy-to-use solution that is highly customizable and compatible with various environments, including global, ES Module, and CommonJS. With FlashyJS, you can create stylish notifications featuring smooth animations, themes, icons, and flexible configuration options.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Lightweight**: Minimal footprint for fast loading.
- **Modern Design**: Clean and stylish notifications.
- **Easy to Use**: Simple API for quick integration.
- **Highly Customizable**: Adjust styles, animations, and settings.
- **Multiple Environments**: Works with global, ES Module, and CommonJS setups.
- **Smooth Animations**: Enhance user experience with fluid transitions.

## Installation

To install FlashyJS, you can use npm or include it directly in your HTML file.

### Using npm

Run the following command in your terminal:

```bash
npm install flashyjs
```

### Directly in HTML

You can also include FlashyJS directly in your HTML file:

```html
<script src="https://cdn.jsdelivr.net/npm/flashyjs/dist/flashy.min.js"></script>
```

## Usage

Using FlashyJS is straightforward. Here’s a basic example of how to create a notification.

### Basic Notification

```javascript
Flashy.notify('This is a notification message!');
```

### Notification with Options

You can customize your notifications by passing an options object:

```javascript
Flashy.notify({
    message: 'This is a customizable notification!',
    duration: 3000, // duration in milliseconds
    type: 'success', // 'info', 'success', 'warning', 'error'
});
```

## Customization

FlashyJS allows you to tailor notifications to fit your design needs. Here are some of the options you can customize:

### Themes

You can set different themes for your notifications. Here’s how to apply a theme:

```javascript
Flashy.setTheme('dark'); // Available themes: 'light', 'dark', 'colorful'
```

### Icons

You can add icons to your notifications. Here’s an example:

```javascript
Flashy.notify({
    message: 'This is a notification with an icon!',
    icon: 'path/to/icon.png',
});
```

### Custom Styles

For advanced users, you can define custom styles:

```css
.flashy-notification {
    border-radius: 8px;
    padding: 10px;
    background-color: #333;
    color: #fff;
}
```

## Examples

### Example 1: Success Notification

```javascript
Flashy.notify({
    message: 'Operation completed successfully!',
    type: 'success',
});
```

### Example 2: Error Notification

```javascript
Flashy.notify({
    message: 'An error occurred. Please try again.',
    type: 'error',
});
```

### Example 3: Info Notification

```javascript
Flashy.notify({
    message: 'This is an informational message.',
    type: 'info',
});
```

### Example 4: Warning Notification

```javascript
Flashy.notify({
    message: 'Warning! Check your input.',
    type: 'warning',
});
```

## Contributing

We welcome contributions to FlashyJS! If you have ideas for new features, improvements, or bug fixes, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes.
4. Submit a pull request with a clear description of your changes.

## License

FlashyJS is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest updates and releases, visit our [Releases](https://github.com/DEEEEEZZ/FlashyJS/releases) section. Here you can download the latest version and view the change log.

Feel free to explore and enhance your web applications with FlashyJS! For more examples and detailed documentation, check the repository or explore the source code. Happy coding!