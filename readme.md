[available on npmjs](https://www.npmjs.com/package/cute-status-codes)
# cute-status-codes

A package that provides cute status codes for your applications.

## Features

- Easy-to-use cute status codes.
- Lightweight and efficient.
- They map to numbers simply.


## Getting Started

### Installation

1. Install cute-status-codes locally.

```npm install cute-status-codes```

### Usage

```JavaScript
import { OK, GONE } from 'cute-status-codes'; // LOOK AT CODE FOR REF
import cors from 'cors';

// SERVERLESS FUNCTION EXAMPLE
export const cloudFunc = (req, res) =>
{
    cors()(req, res, async () =>
    {
        if (?) return res.status(OK).send('text');
        res.sendStatus(GONE);
    });
};
```