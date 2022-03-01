# **Installation**

```
npm i cashfree-elementjs
```

Note: add --save if you are using npm < 5.0.0

# Documentation

Element is our SDK solution for accepting payments when merchants want to display their own UI. Element works by binding itself to your UI elements. It can then process payments by using the values from those elements and initiating payment processing. Read more on:
[https://docs.cashfree.com/docs/element-js]

## Basic Implementation:
```
import { cashfreeSandbox } from 'cashfree-elementjs';
//use import { cashfreeProd } from 'cashfree-elementjs';

cashfreeSandbox.initializeApp({    
    onPaymentSuccess: Function,
    onPaymentFailure: Function,
    onError: Function,
});
```