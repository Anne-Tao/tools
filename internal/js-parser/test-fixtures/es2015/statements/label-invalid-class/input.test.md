# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > statements > label-invalid-class`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2015/statements/label-invalid-class/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/statements/label-invalid-class/input.js"
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
				message: RAW_MARKUP {value: "Unexpected token"}
			}
			location: Object {
				filename: "es2015/statements/label-invalid-class/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 10
					line: 1
				}
				start: Object {
					column: 5
					line: 1
				}
			}
		}
	]
	body: Array [
		JSLabeledStatement {
			loc: Object {
				filename: "es2015/statements/label-invalid-class/input.js"
				end: Object {
					column: 15
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			label: JSIdentifier {
				name: "foo"
				loc: Object {
					filename: "es2015/statements/label-invalid-class/input.js"
					identifierName: "foo"
					end: Object {
						column: 3
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
			}
			body: JSClassDeclaration {
				id: JSBindingIdentifier {
					name: "X"
					loc: Object {
						filename: "es2015/statements/label-invalid-class/input.js"
						identifierName: "X"
						end: Object {
							column: 12
							line: 1
						}
						start: Object {
							column: 11
							line: 1
						}
					}
				}
				loc: Object {
					filename: "es2015/statements/label-invalid-class/input.js"
					end: Object {
						column: 15
						line: 1
					}
					start: Object {
						column: 5
						line: 1
					}
				}
				meta: JSClassHead {
					body: Array []
					implements: undefined
					superClass: undefined
					superTypeParameters: undefined
					typeParameters: undefined
					loc: Object {
						filename: "es2015/statements/label-invalid-class/input.js"
						end: Object {
							column: 15
							line: 1
						}
						start: Object {
							column: 5
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

 es2015/statements/label-invalid-class/input.js:1:5 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unexpected token

    foo: class X {}
         ^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
