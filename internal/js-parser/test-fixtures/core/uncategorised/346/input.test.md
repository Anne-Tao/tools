# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 346`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "core/uncategorised/346/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/346/input.js"
		end: Object {
			column: 1
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
					RAW_MARKUP {value: "Unknown start to an "}
					"statement expression"
				]
			}
			location: Object {
				filename: "core/uncategorised/346/input.js"
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
				filename: "core/uncategorised/346/input.js"
				end: Object {
					column: 1
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "core/uncategorised/346/input.js"
					end: Object {
						column: 1
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

 core/uncategorised/346/input.js:1 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unknown start to an statement expression

    }
    ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
