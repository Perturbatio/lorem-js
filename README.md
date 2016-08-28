# LoremJS

## example:

```javascript
var rules = [
	{
		selector: "main h1",
		numLines: [1, 2],
		maxLength: 32,
	},
	{
		selector: "main p",
		numLines: [3, 5]
	},
	{
		selector: '.full-width',
		numLines: [1,2]
	}
];

var lorem = new Lorem({rules: rules});
lorem.processRules();
```

