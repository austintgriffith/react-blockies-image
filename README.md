# React Blockies Image

An Extension of React-Blockies: https://github.com/AugurProject/react-blockies

Which is a simple port of https://github.com/alexvandesande/blockies  

# Purpose

Works just like react-blockies, but allows for optional parameters to include an image that will have an identicon border for identity verification.

This is useful for projects like https://github.com/gitcoinco/ethavatar where you want to replace your "identicon" with an image, but you want *some* procedurally generated data to verify identity.

# Example:

Works just like normal react-blockies:
```javascript
import Blockies from 'react-blockies-image';

<Blockies
  seed={"austingriffith.eth"}
  scale={10}
/>
```
![Example 1](/example1.png?raw=true "Example 1")

But you can give it a size, border, and image too:
```javascript
import Blockies from 'react-blockies-image';

<Blockies
  seed={"austingriffith.eth"}
  size={200}
  border={10}
  image={"/austin.jpg"}
/>
```
![Example 2](/example2.png?raw=true "Example 2")
