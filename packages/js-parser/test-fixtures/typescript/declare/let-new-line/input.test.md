# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > declare > let-new-line`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/declare/let-new-line/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/declare/let-new-line/input.ts"
		end: Object {
			column: 0
			index: 15
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/declare/let-new-line/input.ts"
				end: Object {
					column: 7
					index: 7
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "declare"
				loc: Object {
					filename: "typescript/declare/let-new-line/input.ts"
					identifierName: "declare"
					end: Object {
						column: 7
						index: 7
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
			}
		}
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/declare/let-new-line/input.ts"
				end: Object {
					column: 6
					index: 14
					line: 2
				}
				start: Object {
					column: 0
					index: 8
					line: 2
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/declare/let-new-line/input.ts"
					end: Object {
						column: 6
						index: 14
						line: 2
					}
					start: Object {
						column: 0
						index: 8
						line: 2
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "typescript/declare/let-new-line/input.ts"
								identifierName: "x"
								end: Object {
									column: 5
									index: 13
									line: 2
								}
								start: Object {
									column: 4
									index: 12
									line: 2
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/declare/let-new-line/input.ts"
							end: Object {
								column: 5
								index: 13
								line: 2
							}
							start: Object {
								column: 4
								index: 12
								line: 2
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