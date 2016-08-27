# LoremJS

## example:

```javascript
		var rules = [
			{
				selector: "main p:first-of-type",
				numLines: [1, 2]
			},
			{
				selector: "main p:not(:first-of-type)",
				numLines: [3, 8]
			}
		];

		var lorem = new Lorem({rules: rules});
		lorem.processRules();
```

