# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 202`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2015/uncategorised/202/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/202/input.js"
		end: Object {
			column: 2
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse"}]
			description: Object {
				advice: Array []
				category: "parse"
				categoryValue: "js"
				message: Array [
					RAW_MARKUP {value: "Expected number in radix "}
					"8"
				]
			}
			location: Object {
				filename: "es2015/uncategorised/202/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 2
					line: 1
				}
				start: Object {
					column: 2
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/202/input.js"
				end: Object {
					column: 2
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSNumericLiteral {
				value: 0
				format: "octal"
				raw: "0O"
				loc: Object {
					filename: "es2015/uncategorised/202/input.js"
					end: Object {
						column: 2
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```

 es2015/uncategorised/202/input.js:1:2 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected number in radix 8

    0O
      ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
