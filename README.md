# th-sort
Multithread Quicksort

Simple quicksort algorythm in other thread. It is many times faster then sync/async sorting when you need to sort many items. 

# Example

[sandbox](https://codesandbox.io/s/qvpm7qvr5j) where you can sort one array in main thread and in separated thread.

# Usage

```js
import thsort from 'th-sort';

(async () => {
	// array is defined somewhere earlier
    const sorted = await tsort(array);
})()

// Or

tsort(array)
	.then((sorted) => {

	})
```

# Installing

```bash
npm i --save th-sort
```
