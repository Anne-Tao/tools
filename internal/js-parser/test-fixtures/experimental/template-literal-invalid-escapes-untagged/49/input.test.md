# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > template-literal-invalid-escapes-untagged > 49`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "experimental/template-literal-invalid-escapes-untagged/49/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/template-literal-invalid-escapes-untagged/49/input.js"
		end: Object {
			column: 7
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
				message: RAW_MARKUP {value: "Invalid escape sequence in template"}
			}
			location: Object {
				filename: "experimental/template-literal-invalid-escapes-untagged/49/input.js"
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
				filename: "experimental/template-literal-invalid-escapes-untagged/49/input.js"
				end: Object {
					column: 7
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
					filename: "experimental/template-literal-invalid-escapes-untagged/49/input.js"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				quasis: Array [
					JSTemplateElement {
						cooked: "\\u{\\\\"
						raw: "\\u{\\\\"
						tail: true
						loc: Object {
							filename: "experimental/template-literal-invalid-escapes-untagged/49/input.js"
							end: Object {
								column: 6
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

 experimental/template-literal-invalid-escapes-untagged/49/input.js:1:2 parse(js) ━━━━━━━━━━━━━━━━━━

  ✖ Invalid escape sequence in template

    `\u{\\`
      ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
