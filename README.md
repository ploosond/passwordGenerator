# Password Generator

A React-based password generator that creates secure, customizable passwords.

## Features

- Generate random passwords with customizable length
- Include/exclude numbers
- Include/exclude special characters
- Copy password to clipboard functionality
- Real-time password generation

## Technical Details

Built with:

- React.js
- useState for state management
- useCallback for performance optimization
- useRef for DOM manipulation
- useEffect for side effects

## How It Works

The application uses React's state management to generate secure passwords based on user preferences:

- Allows selecting password length
- Toggle numbers (0-9)
- Toggle special characters (!@#$%^&\*-\_=[]{})
- Implements secure random character selection
- Provides instant copy-to-clipboard functionality

## Installation

```bash
git clone https://github.com/ploosond/passwordGenerator
cd passwordGenerator
npm install
npm start
```
