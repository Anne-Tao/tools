# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-yield > yield-generator-arrow-function-body`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
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
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "g"
				loc: Object {
					filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
					identifierName: "g"
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
				filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
				end: Object {
					column: 39
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: true
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
					end: Object {
						column: 13
						line: 1
					}
					start: Object {
						column: 11
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
					end: Object {
						column: 39
						line: 1
					}
					start: Object {
						column: 14
						line: 1
					}
				}
				body: Array [
					JSExpressionStatement {
						loc: Object {
							filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
							end: Object {
								column: 37
								line: 1
							}
							start: Object {
								column: 16
								line: 1
							}
						}
						expression: JSArrowFunctionExpression {
							loc: Object {
								filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
								end: Object {
									column: 36
									line: 1
								}
								start: Object {
									column: 16
									line: 1
								}
							}
							head: JSFunctionHead {
								async: false
								hasHoistedVars: false
								rest: undefined
								returnType: undefined
								thisType: undefined
								loc: Object {
									filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
									end: Object {
										column: 22
										line: 1
									}
									start: Object {
										column: 16
										line: 1
									}
								}
								params: Array [
									JSBindingIdentifier {
										name: "z"
										loc: Object {
											filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
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
								]
							}
							body: JSBlockStatement {
								directives: Array []
								loc: Object {
									filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
									end: Object {
										column: 36
										line: 1
									}
									start: Object {
										column: 23
										line: 1
									}
								}
								body: Array [
									JSExpressionStatement {
										loc: Object {
											filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
											end: Object {
												column: 34
												line: 1
											}
											start: Object {
												column: 25
												line: 1
											}
										}
										expression: JSBinaryExpression {
											operator: "+"
											loc: Object {
												filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
												end: Object {
													column: 34
													line: 1
												}
												start: Object {
													column: 25
													line: 1
												}
											}
											left: JSReferenceIdentifier {
												name: "yield"
												loc: Object {
													filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
													identifierName: "yield"
													end: Object {
														column: 30
														line: 1
													}
													start: Object {
														column: 25
														line: 1
													}
												}
											}
											right: JSReferenceIdentifier {
												name: "z"
												loc: Object {
													filename: "esprima/es2015-yield/yield-generator-arrow-function-body/input.js"
													identifierName: "z"
													end: Object {
														column: 34
														line: 1
													}
													start: Object {
														column: 33
														line: 1
													}
												}
											}
										}
									}
								]
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
