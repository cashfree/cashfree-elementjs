# **Installation**

```
npm i cashfree-elementjs
```

Note: add --save if you are using npm < 5.0.0

# Documentation

Drop is our pre-built UI solution for accepting payments. Drop works by displaying payment components we call as drops at any place you want in your page. It can either display all the payment components at one place or different places depending on your need. Read more on:
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