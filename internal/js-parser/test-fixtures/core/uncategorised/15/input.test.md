# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 15`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/uncategorised/15/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/15/input.js"
		end: Object {
			column: 7
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "core/uncategorised/15/input.js"
				end: Object {
					column: 7
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "core/uncategorised/15/input.js"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				right: JSArrayExpression {
					elements: Array []
					loc: Object {
						filename: "core/uncategorised/15/input.js"
						end: Object {
							column: 7
							line: 1
						}
						start: Object {
							column: 5
							line: 1
						}
					}
				}
				left: JSAssignmentIdentifier {
					name: "T\u203f"
					loc: Object {
						filename: "core/uncategorised/15/input.js"
						identifierName: "T\u203f"
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
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
