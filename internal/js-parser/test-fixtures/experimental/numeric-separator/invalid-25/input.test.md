# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > numeric-separator > invalid-25`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "experimental/numeric-separator/invalid-25/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/numeric-separator/invalid-25/input.js"
		end: Object {
			column: 0
			line: 2
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
				message: RAW_MARKUP {value: "Invalid or unexpected int token"}
			}
			location: Object {
				filename: "experimental/numeric-separator/invalid-25/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 0
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/numeric-separator/invalid-25/input.js"
				end: Object {
					column: 5
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSNumericLiteral {
				value: 1
				format: "octal"
				raw: "0o01_"
				loc: Object {
					filename: "experimental/numeric-separator/invalid-25/input.js"
					end: Object {
						column: 5
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/numeric-separator/invalid-25/input.js"
				end: Object {
					column: 6
					line: 1
				}
				start: Object {
					column: 5
					line: 1
				}
			}
			expression: JSNumericLiteral {
				value: 8
				format: undefined
				raw: "8"
				loc: Object {
					filename: "experimental/numeric-separator/invalid-25/input.js"
					end: Object {
						column: 6
						line: 1
					}
					start: Object {
						column: 5
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

 experimental/numeric-separator/invalid-25/input.js:1 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Invalid or unexpected int token

    0o01_8
    ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
