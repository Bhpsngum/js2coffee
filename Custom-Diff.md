## Customized differences from original js2coffee
### Array
- Array with a single element is now having no appended space: `[ 1 ]` --> `[1]`
- Array with multiple elements are now joining in one line, separating by `,`: `1<NEWLINE>2<NEWLINE>3` --> `[1,2,3]`
