# simple-react-modal-component
A simple react modal component

## Prerequisites

![Npm](https://img.shields.io/badge/Npm-v10.2.1-blue)
![Node](https://img.shields.io/badge/Node-v21.1.0-blue)
![React](https://img.shields.io/badge/React-v18.2.0-blue)
![React-DOM](https://img.shields.io/badge/React--DOM-v18.2.0-blue)

## Install


```bash
npm i react-modal-adrienlzl
```
You can check your node_modules folder to make sure the package has been installed correctly

How to use this modal

## Usage


```jsx
import React, { useState } from 'react';
import { Modal } from '';

function App() {
    const [isOpen, setIsOpen] = useState(false);
    
    return (
        <div>
          <button onClick={() => setIsOpen(true)}>Click to open</button>
          <Modal
                isOpen={isOpen}
                onClose={() => setIsOpen(false)}
                onExternalClick={() => setIsOpen(false)}
            >
                Modal message !
            </Modal>
        </div>
    );
}

export default App;
```
## Author

**Adrien Lazaille**

+ [github/adrienlzl](https://github.com/adrienlzl?tab=repositories)
