# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-left-hand-side > migrated_0016`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/expression-left-hand-side/migrated_0016/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/expression-left-hand-side/migrated_0016/input.js"
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
				filename: "esprima/expression-left-hand-side/migrated_0016/input.js"
				end: Object {
					column: 21
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSMemberExpression {
				loc: Object {
					filename: "esprima/expression-left-hand-side/migrated_0016/input.js"
					end: Object {
						column: 21
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				property: JSStaticMemberProperty {
					value: JSIdentifier {
						name: "galaxies"
						loc: Object {
							filename: "esprima/expression-left-hand-side/migrated_0016/input.js"
							identifierName: "galaxies"
							end: Object {
								column: 21
								line: 1
							}
							start: Object {
								column: 13
								line: 1
							}
						}
					}
					loc: Object {
						filename: "esprima/expression-left-hand-side/migrated_0016/input.js"
						identifierName: "galaxies"
						end: Object {
							column: 21
							line: 1
						}
						start: Object {
							column: 13
							line: 1
						}
					}
				}
				object: JSCallExpression {
					loc: Object {
						filename: "esprima/expression-left-hand-side/migrated_0016/input.js"
						end: Object {
							column: 12
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
					callee: JSReferenceIdentifier {
						name: "universe"
						loc: Object {
							filename: "esprima/expression-left-hand-side/migrated_0016/input.js"
							identifierName: "universe"
							end: Object {
								column: 8
								line: 1
							}
							start: Object {
								column: 0
								line: 1
							}
						}
					}
					arguments: Array [
						JSNumericLiteral {
							value: 42
							format: undefined
							raw: "42"
							loc: Object {
								filename: "esprima/expression-left-hand-side/migrated_0016/input.js"
								end: Object {
									column: 11
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
						}
					]
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
