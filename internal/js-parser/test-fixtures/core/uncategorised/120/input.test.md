# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 120`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/uncategorised/120/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/120/input.js"
		end: Object {
			column: 29
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
				filename: "core/uncategorised/120/input.js"
				end: Object {
					column: 29
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSMemberExpression {
				loc: Object {
					filename: "core/uncategorised/120/input.js"
					end: Object {
						column: 29
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				property: JSStaticMemberProperty {
					value: JSIdentifier {
						name: "solarsystem"
						loc: Object {
							filename: "core/uncategorised/120/input.js"
							identifierName: "solarsystem"
							end: Object {
								column: 29
								line: 1
							}
							start: Object {
								column: 18
								line: 1
							}
						}
					}
					loc: Object {
						filename: "core/uncategorised/120/input.js"
						identifierName: "solarsystem"
						end: Object {
							column: 29
							line: 1
						}
						start: Object {
							column: 18
							line: 1
						}
					}
				}
				object: JSMemberExpression {
					loc: Object {
						filename: "core/uncategorised/120/input.js"
						end: Object {
							column: 17
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
					object: JSReferenceIdentifier {
						name: "universe"
						loc: Object {
							filename: "core/uncategorised/120/input.js"
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
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "milkyway"
							loc: Object {
								filename: "core/uncategorised/120/input.js"
								identifierName: "milkyway"
								end: Object {
									column: 17
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
						}
						loc: Object {
							filename: "core/uncategorised/120/input.js"
							identifierName: "milkyway"
							end: Object {
								column: 17
								line: 1
							}
							start: Object {
								column: 9
								line: 1
							}
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
