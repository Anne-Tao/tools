# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 410`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "core/uncategorised/410/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/410/input.js"
		end: Object {
			column: 8
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
				message: RAW_MARKUP {value: "Unexpected token"}
			}
			location: Object {
				filename: "core/uncategorised/410/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 7
					line: 1
				}
				start: Object {
					column: 6
					line: 1
				}
			}
		}
	]
	body: Array [
		JSBreakStatement {
			label: undefined
			loc: Object {
				filename: "core/uncategorised/410/input.js"
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
		JSExpressionStatement {
			loc: Object {
				filename: "core/uncategorised/410/input.js"
				end: Object {
					column: 8
					line: 1
				}
				start: Object {
					column: 6
					line: 1
				}
			}
			expression: JSNumericLiteral {
				value: 1
				format: undefined
				raw: "1"
				loc: Object {
					filename: "core/uncategorised/410/input.js"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 6
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

 core/uncategorised/410/input.js:1:6 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unexpected token

    break 1;
          ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
