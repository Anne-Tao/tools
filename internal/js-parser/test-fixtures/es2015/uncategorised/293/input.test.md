# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 293`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "es2015/uncategorised/293/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/293/input.js"
		end: Object {
			column: 14
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
					"if test"
				]
			}
			location: Object {
				filename: "es2015/uncategorised/293/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 6
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
		JSIfStatement {
			alternate: undefined
			loc: Object {
				filename: "es2015/uncategorised/293/input.js"
				end: Object {
					column: 14
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			test: JSSequenceExpression {
				loc: Object {
					filename: "es2015/uncategorised/293/input.js"
					end: Object {
						column: 9
						line: 1
					}
					start: Object {
						column: 4
						line: 1
					}
				}
				expressions: Array [
					JSReferenceIdentifier {
						name: "b"
						loc: Object {
							filename: "es2015/uncategorised/293/input.js"
							identifierName: "b"
							end: Object {
								column: 5
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
					}
					JSReferenceIdentifier {
						name: "INVALID_PLACEHOLDER"
						loc: Object {
							filename: "es2015/uncategorised/293/input.js"
							end: Object {
								column: 9
								line: 1
							}
							start: Object {
								column: 6
								line: 1
							}
						}
					}
				]
			}
			consequent: JSExpressionStatement {
				loc: Object {
					filename: "es2015/uncategorised/293/input.js"
					end: Object {
						column: 14
						line: 1
					}
					start: Object {
						column: 9
						line: 1
					}
				}
				expression: JSSequenceExpression {
					loc: Object {
						filename: "es2015/uncategorised/293/input.js"
						end: Object {
							column: 13
							line: 1
						}
						start: Object {
							column: 9
							line: 1
						}
					}
					expressions: Array [
						JSReferenceIdentifier {
							name: "a"
							loc: Object {
								filename: "es2015/uncategorised/293/input.js"
								identifierName: "a"
								end: Object {
									column: 10
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
						}
						JSReferenceIdentifier {
							name: "INVALID_PLACEHOLDER"
							loc: Object {
								filename: "es2015/uncategorised/293/input.js"
								end: Object {
									column: 13
									line: 1
								}
								start: Object {
									column: 12
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

 es2015/uncategorised/293/input.js:1:6 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unknown start to an if test

    if (b,...a, );
          ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
