# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > 15`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2017/async-functions/15/input.js"
	hasHoistedVars: true
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2017/async-functions/15/input.js"
		end: Object {
			column: 54
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "es2017/async-functions/15/input.js"
				end: Object {
					column: 54
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "es2017/async-functions/15/input.js"
					end: Object {
						column: 54
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "o"
							loc: Object {
								filename: "es2017/async-functions/15/input.js"
								identifierName: "o"
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
						loc: Object {
							filename: "es2017/async-functions/15/input.js"
							end: Object {
								column: 54
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
						init: JSObjectExpression {
							loc: Object {
								filename: "es2017/async-functions/15/input.js"
								end: Object {
									column: 54
									line: 1
								}
								start: Object {
									column: 8
									line: 1
								}
							}
							properties: Array [
								JSObjectProperty {
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "a"
											loc: Object {
												filename: "es2017/async-functions/15/input.js"
												identifierName: "a"
												end: Object {
													column: 11
													line: 1
												}
												start: Object {
													column: 10
													line: 1
												}
											}
										}
										loc: Object {
											filename: "es2017/async-functions/15/input.js"
											end: Object {
												column: 11
												line: 1
											}
											start: Object {
												column: 10
												line: 1
											}
										}
									}
									value: JSNumericLiteral {
										value: 1
										format: undefined
										raw: "1"
										loc: Object {
											filename: "es2017/async-functions/15/input.js"
											end: Object {
												column: 14
												line: 1
											}
											start: Object {
												column: 13
												line: 1
											}
										}
									}
									loc: Object {
										filename: "es2017/async-functions/15/input.js"
										end: Object {
											column: 14
											line: 1
										}
										start: Object {
											column: 10
											line: 1
										}
									}
								}
								JSObjectMethod {
									kind: "method"
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "foo"
											loc: Object {
												filename: "es2017/async-functions/15/input.js"
												identifierName: "foo"
												end: Object {
													column: 25
													line: 1
												}
												start: Object {
													column: 22
													line: 1
												}
											}
										}
										loc: Object {
											filename: "es2017/async-functions/15/input.js"
											end: Object {
												column: 25
												line: 1
											}
											start: Object {
												column: 22
												line: 1
											}
										}
									}
									loc: Object {
										filename: "es2017/async-functions/15/input.js"
										end: Object {
											column: 52
											line: 1
										}
										start: Object {
											column: 16
											line: 1
										}
									}
									head: JSFunctionHead {
										async: true
										generator: false
										hasHoistedVars: false
										rest: undefined
										returnType: undefined
										thisType: undefined
										typeParameters: undefined
										loc: Object {
											filename: "es2017/async-functions/15/input.js"
											end: Object {
												column: 34
												line: 1
											}
											start: Object {
												column: 25
												line: 1
											}
										}
										params: Array [
											JSBindingIdentifier {
												name: "promise"
												loc: Object {
													filename: "es2017/async-functions/15/input.js"
													identifierName: "promise"
													end: Object {
														column: 33
														line: 1
													}
													start: Object {
														column: 26
														line: 1
													}
												}
												meta: JSPatternMeta {
													optional: undefined
													typeAnnotation: undefined
													loc: Object {
														filename: "es2017/async-functions/15/input.js"
														end: Object {
															column: 33
															line: 1
														}
														start: Object {
															column: 26
															line: 1
														}
													}
												}
											}
										]
									}
									body: JSBlockStatement {
										directives: Array []
										loc: Object {
											filename: "es2017/async-functions/15/input.js"
											end: Object {
												column: 52
												line: 1
											}
											start: Object {
												column: 35
												line: 1
											}
										}
										body: Array [
											JSExpressionStatement {
												loc: Object {
													filename: "es2017/async-functions/15/input.js"
													end: Object {
														column: 50
														line: 1
													}
													start: Object {
														column: 37
														line: 1
													}
												}
												expression: JSAwaitExpression {
													loc: Object {
														filename: "es2017/async-functions/15/input.js"
														end: Object {
															column: 50
															line: 1
														}
														start: Object {
															column: 37
															line: 1
														}
													}
													argument: JSReferenceIdentifier {
														name: "promise"
														loc: Object {
															filename: "es2017/async-functions/15/input.js"
															identifierName: "promise"
															end: Object {
																column: 50
																line: 1
															}
															start: Object {
																column: 43
																line: 1
															}
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
