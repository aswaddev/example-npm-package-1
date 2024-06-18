# Button Component Library

Welcome to the **Button Component Library**! This is a simple React component library designed for testing and learning purposes.

## Overview

This library offers a reusable `Button` component that supports customizable styles. You can pass in various props, including `color`, `backgroundColor`, and all the default button props available in
React.

## Installation

You can install the package using npm:

```
bash npm install @aswadali/compolib
```

Or with yarn:

```
bash yarn add @aswadali/compolib
```

## Usage

Here's a quick example of how to use the `Button` component in your React application:

```jsx
import React from 'react';
import Button from '@aswadali/compolib';

const App = () => {
    return (
        <div>
            <Button color="white" backgroundColor="blue" onClick={() => alert('Button clicked!')}>
                Click Me
            </Button>
        </div>
    );
};

export default App;
```

## Props

The `Button` component supports the following props:

-   **color**: Sets the text color of the button.
-   **backgroundColor**: Sets the background color of the button.
-   **...props**: Accepts all default button props from React, such as `onClick`, `disabled`, `type`, etc.

### Example

```jsx
<Button color="white" backgroundColor="green" onClick={() => console.log('Green Button clicked!')}>
    Green Button
</Button>
```

## Contributing

Feel free to contribute to this library! Whether it's reporting a bug, suggesting improvements, or submitting a pull request, your contributions are welcome.

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push to your branch.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

This library was created for learning and testing purposes. Thanks to the open-source community for their support and contributions.

---

Happy coding! 🎉

If you have any questions or need further assistance, please feel free to reach out.
