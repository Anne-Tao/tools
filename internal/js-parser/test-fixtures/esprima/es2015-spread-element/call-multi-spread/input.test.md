# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-spread-element > call-multi-spread`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
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
				filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
				end: Object {
					column: 20
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSCallExpression {
				loc: Object {
					filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
					end: Object {
						column: 19
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "f"
					loc: Object {
						filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
						identifierName: "f"
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
				arguments: Array [
					JSSpreadElement {
						loc: Object {
							filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
							end: Object {
								column: 6
								line: 1
							}
							start: Object {
								column: 2
								line: 1
							}
						}
						argument: JSReferenceIdentifier {
							name: "x"
							loc: Object {
								filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
								identifierName: "x"
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
					JSSpreadElement {
						loc: Object {
							filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
							end: Object {
								column: 12
								line: 1
							}
							start: Object {
								column: 8
								line: 1
							}
						}
						argument: JSReferenceIdentifier {
							name: "y"
							loc: Object {
								filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
								identifierName: "y"
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
					}
					JSSpreadElement {
						loc: Object {
							filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
							end: Object {
								column: 18
								line: 1
							}
							start: Object {
								column: 14
								line: 1
							}
						}
						argument: JSReferenceIdentifier {
							name: "z"
							loc: Object {
								filename: "esprima/es2015-spread-element/call-multi-spread/input.js"
								identifierName: "z"
								end: Object {
									column: 18
									line: 1
								}
								start: Object {
									column: 17
									line: 1
								}
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
