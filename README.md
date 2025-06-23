# MUI Input Chips

A flexible and customizable input chips component for React applications using Material-UI.

## Installation

```bash
npm install mui-input-chips
```

## Usage

```jsx
import { useState } from 'react'
import { InputChips } from 'mui-input-chips'

function App() {
  const [chips, setChips] = useState(['apple', 'banana'])

  return <InputChips chipValues={chips} setChipValues={setChips} onChange={setChips} />
}
```

## Props

| Prop         | Type                         | Default | Description                      |
| ------------ | ---------------------------- | ------- | -------------------------------- |
| `chipValues` | `string[]`                   | `[]`    | Array of chip values             |
| `onChange`   | `(values: string[]) => void` | -       | Callback fired when chips change |

## Features

- ✨ Material-UI design system integration
- ⌨️ Keyboard navigation (Enter to add, Backspace to remove)
- ♿ Accessibility compliant

## Requirements

- React 19.0+
- Material-UI 5.0+

## License

MIT

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
