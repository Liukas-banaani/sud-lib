# Sud-lib: A Customizable React UI Component Library 🌌

[![Release](https://img.shields.io/badge/Release-v1.0.0-blue)](https://github.com/Liukas-banaani/sud-lib/releases)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
- [Customization](#customization)
- [Dark Mode Support](#dark-mode-support)
- [Contributing](#contributing)
- [License](#license)

## Overview

Sud-lib is a React UI component library designed for developers who need a flexible and customizable solution for their projects. With dark mode support and reusable components, Sud-lib aims to simplify the UI development process. 

Explore the [Releases](https://github.com/Liukas-banaani/sud-lib/releases) section to find the latest updates and download the necessary files.

## Features

- **Reusable Components**: Build your UI faster with pre-built components.
- **Customizable Styles**: Tailor the look and feel of your components.
- **Dark Mode Support**: Easily switch between light and dark themes.
- **Utility-Style Class Names**: Use simple class names for styling.
- **Well-Documented**: Comprehensive documentation for each component.

## Installation

To install Sud-lib, you can use npm or yarn. Run one of the following commands in your terminal:

```bash
npm install sud-lib
```

or

```bash
yarn add sud-lib
```

Once installed, you can import the components you need into your React project.

## Usage

Here’s a simple example of how to use a button component from Sud-lib:

```jsx
import React from 'react';
import { Button } from 'sud-lib';

const App = () => {
  return (
    <div>
      <Button label="Click Me" />
    </div>
  );
};

export default App;
```

You can customize the button's appearance using props or by applying custom styles.

## Components

Sud-lib includes a variety of components to help you build your UI:

- **Button**: A versatile button component.
- **Card**: Use cards to display content in a structured way.
- **Modal**: Create modals for alerts or additional information.
- **Input**: Standard input fields with customizable styles.
- **Tooltip**: Display additional information on hover.

Each component comes with its own set of props and examples. Check the documentation for more details.

## Customization

You can easily customize the styles of the components to fit your design requirements. Here’s how:

1. **Using Props**: Most components accept props that allow you to change colors, sizes, and other styles.
2. **CSS Overrides**: You can apply your own CSS classes to override default styles.
3. **Theme Provider**: Use a theme provider to set global styles for all components.

## Dark Mode Support

Sud-lib includes built-in support for dark mode. You can toggle between light and dark themes with a simple prop. Here’s an example:

```jsx
import React, { useState } from 'react';
import { ThemeProvider } from 'sud-lib';

const App = () => {
  const [darkMode, setDarkMode] = useState(false);

  return (
    <ThemeProvider darkMode={darkMode}>
      <button onClick={() => setDarkMode(!darkMode)}>
        Toggle Dark Mode
      </button>
      <Button label="Click Me" />
    </ThemeProvider>
  );
};

export default App;
```

## Contributing

We welcome contributions to Sud-lib! If you want to help improve the library, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and open a pull request.

Please ensure that your code follows the existing style and includes appropriate tests.

## License

Sud-lib is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

For more updates, visit the [Releases](https://github.com/Liukas-banaani/sud-lib/releases) section to download the latest version.