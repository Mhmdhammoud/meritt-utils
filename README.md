# Meritt Utility functions

This is a collection of utility functions that are often used in Meritt projects.

## Installation

For npm:

```bash
npm install @mhmdhammoud/meritt-utils
```

or for yarn:

```bash
yarn add @mhmdhammoud/meritt-utils
```

## Usage

```typescript
// Import the classes you need
import {Crypto, Formatter} from '@mhmdhammoud/meritt-utils'

// Example of creating a product slug
const slug = Formatter.slugify('My Product Name') // my-product-name

// Example of encrypting and decrypting a string

const encryptedMessage = Crypto.encrypt('Hello World', 7) // [23,235,141,414]
```
