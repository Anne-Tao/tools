# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > escape-template > non-octal-nine`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/escape-template/non-octal-nine/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/escape-template/non-octal-nine/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "core/escape-template/non-octal-nine/input.js"
				end: Object {
					column: 5
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSTemplateLiteral {
				expressions: Array []
				loc: Object {
					filename: "core/escape-template/non-octal-nine/input.js"
					end: Object {
						column: 4
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				quasis: Array [
					JSTemplateElement {
						cooked: "9"
						raw: "\\9"
						tail: true
						loc: Object {
							filename: "core/escape-template/non-octal-nine/input.js"
							end: Object {
								column: 3
								line: 1
							}
							start: Object {
								column: 1
								line: 1
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
