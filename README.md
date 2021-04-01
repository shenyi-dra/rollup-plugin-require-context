# rollup-plugin-require-context

rollup plugin for resovling webpack require-context.

## reference

repo: https://github.com/elcarim5efil/rollup-plugin-require-context

issue:
https://github.com/elcarim5efil/rollup-plugin-require-context/issues/17

Due to this repo has not been updated for quite long time, and have created an issue these days. Hope it will fix very soon. So i have created my own repo to temperary fix this issue for now.


## usage

```javascript
import requireContext from 'rollup-plugin-require-context';

export default {
  input: 'main.js',
  output: {
    file: 'bundle.js',
    format: 'iife'
  },
  plugins: [
    requireContext()
  ]
};
```
