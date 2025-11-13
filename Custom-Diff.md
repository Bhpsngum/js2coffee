## Customized differences from original js2coffee
### Array
- Array with a single element is now having no appended space
```coffee
# JS
[1]

# Output (old)
[ 1 ]

# Output (new)
[1]
```
- Array with multiple elements are now having separator of `,` or `, ` instead of newline
```coffee
# JS
[1, 2, 3, { a: 1, b: 2}]

# Output (old)
[
	1
	2
	3
]

# Output (new)
[1,2,3, {
	a: 1
	b: 2
}]
```

### Object
- Object properties are always shown in next lines regardless of properties count
```coffee
# JS
object = { a: 1 }

# Output (old)
object = a: 1

# Output (new)
object =
	a: 1
```
