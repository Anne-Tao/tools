# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `comments > basic > call-expression-function-argument`

### `ast`

```javascript
JSRoot {
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "comments/basic/call-expression-function-argument/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "comments/basic/call-expression-function-argument/input.js"
		end: Object {
			column: 0
			line: 7
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	comments: Array [
		CommentLine {
			id: "0"
			value: " one"
			loc: Object {
				filename: "comments/basic/call-expression-function-argument/input.js"
				end: Object {
					column: 8
					line: 3
				}
				start: Object {
					column: 2
					line: 3
				}
			}
		}
		CommentLine {
			id: "1"
			value: " two"
			loc: Object {
				filename: "comments/basic/call-expression-function-argument/input.js"
				end: Object {
					column: 6
					line: 5
				}
				start: Object {
					column: 0
					line: 5
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "comments/basic/call-expression-function-argument/input.js"
				end: Object {
					column: 2
					line: 6
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSCallExpression {
				loc: Object {
					filename: "comments/basic/call-expression-function-argument/input.js"
					end: Object {
						column: 1
						line: 6
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "test"
					loc: Object {
						filename: "comments/basic/call-expression-function-argument/input.js"
						identifierName: "test"
						end: Object {
							column: 4
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
				}
				arguments: Array [
					JSFunctionExpression {
						id: undefined
						trailingComments: Array ["1"]
						loc: Object {
							filename: "comments/basic/call-expression-function-argument/input.js"
							end: Object {
								column: 1
								line: 4
							}
							start: Object {
								column: 5
								line: 1
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: true
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "comments/basic/call-expression-function-argument/input.js"
								end: Object {
									column: 15
									line: 1
								}
								start: Object {
									column: 13
									line: 1
								}
							}
						}
						body: JSBlockStatement {
							directives: Array []
							trailingComments: Array ["1"]
							loc: Object {
								filename: "comments/basic/call-expression-function-argument/input.js"
								end: Object {
									column: 1
									line: 4
								}
								start: Object {
									column: 16
									line: 1
								}
							}
							body: Array [
								JSVariableDeclarationStatement {
									trailingComments: Array ["0"]
									loc: Object {
										filename: "comments/basic/call-expression-function-argument/input.js"
										end: Object {
											column: 12
											line: 2
										}
										start: Object {
											column: 2
											line: 2
										}
									}
									declaration: JSVariableDeclaration {
										kind: "var"
										trailingComments: undefined
										loc: Object {
											filename: "comments/basic/call-expression-function-argument/input.js"
											end: Object {
												column: 12
												line: 2
											}
											start: Object {
												column: 2
												line: 2
											}
										}
										declarations: Array [
											JSVariableDeclarator {
												id: JSBindingIdentifier {
													name: "a"
													loc: Object {
														filename: "comments/basic/call-expression-function-argument/input.js"
														identifierName: "a"
														end: Object {
															column: 7
															line: 2
														}
														start: Object {
															column: 6
															line: 2
														}
													}
												}
												loc: Object {
													filename: "comments/basic/call-expression-function-argument/input.js"
													end: Object {
														column: 11
														line: 2
													}
													start: Object {
														column: 6
														line: 2
													}
												}
												init: JSNumericLiteral {
													value: 1
													format: undefined
													raw: "1"
													loc: Object {
														filename: "comments/basic/call-expression-function-argument/input.js"
														end: Object {
															column: 11
															line: 2
														}
														start: Object {
															column: 10
															line: 2
														}
													}
												}
											}
										]
									}
								}
							]
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
