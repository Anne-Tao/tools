# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `comments > basic > switch-function-call-no-semicolon`

### `ast`

```javascript
JSRoot {
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "comments/basic/switch-function-call-no-semicolon/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "comments/basic/switch-function-call-no-semicolon/input.js"
		end: Object {
			column: 0
			line: 8
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	comments: Array [
		CommentLine {
			id: "0"
			value: " comment"
			loc: Object {
				filename: "comments/basic/switch-function-call-no-semicolon/input.js"
				end: Object {
					column: 14
					line: 4
				}
				start: Object {
					column: 4
					line: 4
				}
			}
		}
	]
	body: Array [
		JSSwitchStatement {
			loc: Object {
				filename: "comments/basic/switch-function-call-no-semicolon/input.js"
				end: Object {
					column: 1
					line: 7
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			discriminant: JSReferenceIdentifier {
				name: "x"
				loc: Object {
					filename: "comments/basic/switch-function-call-no-semicolon/input.js"
					identifierName: "x"
					end: Object {
						column: 8
						line: 1
					}
					start: Object {
						column: 7
						line: 1
					}
				}
			}
			cases: Array [
				JSSwitchCase {
					trailingComments: Array ["0"]
					loc: Object {
						filename: "comments/basic/switch-function-call-no-semicolon/input.js"
						end: Object {
							column: 20
							line: 3
						}
						start: Object {
							column: 2
							line: 2
						}
					}
					test: JSNumericLiteral {
						value: 1
						format: undefined
						raw: "1"
						loc: Object {
							filename: "comments/basic/switch-function-call-no-semicolon/input.js"
							end: Object {
								column: 8
								line: 2
							}
							start: Object {
								column: 7
								line: 2
							}
						}
					}
					consequent: Array [
						JSExpressionStatement {
							trailingComments: undefined
							loc: Object {
								filename: "comments/basic/switch-function-call-no-semicolon/input.js"
								end: Object {
									column: 20
									line: 3
								}
								start: Object {
									column: 4
									line: 3
								}
							}
							expression: JSCallExpression {
								trailingComments: undefined
								loc: Object {
									filename: "comments/basic/switch-function-call-no-semicolon/input.js"
									end: Object {
										column: 20
										line: 3
									}
									start: Object {
										column: 4
										line: 3
									}
								}
								arguments: Array [
									JSStringLiteral {
										value: "1"
										loc: Object {
											filename: "comments/basic/switch-function-call-no-semicolon/input.js"
											end: Object {
												column: 19
												line: 3
											}
											start: Object {
												column: 16
												line: 3
											}
										}
									}
								]
								callee: JSMemberExpression {
									loc: Object {
										filename: "comments/basic/switch-function-call-no-semicolon/input.js"
										end: Object {
											column: 15
											line: 3
										}
										start: Object {
											column: 4
											line: 3
										}
									}
									object: JSReferenceIdentifier {
										name: "console"
										loc: Object {
											filename: "comments/basic/switch-function-call-no-semicolon/input.js"
											identifierName: "console"
											end: Object {
												column: 11
												line: 3
											}
											start: Object {
												column: 4
												line: 3
											}
										}
									}
									property: JSStaticMemberProperty {
										value: JSIdentifier {
											name: "log"
											loc: Object {
												filename: "comments/basic/switch-function-call-no-semicolon/input.js"
												identifierName: "log"
												end: Object {
													column: 15
													line: 3
												}
												start: Object {
													column: 12
													line: 3
												}
											}
										}
										loc: Object {
											filename: "comments/basic/switch-function-call-no-semicolon/input.js"
											identifierName: "log"
											end: Object {
												column: 15
												line: 3
											}
											start: Object {
												column: 12
												line: 3
											}
										}
									}
								}
							}
						}
					]
				}
				JSSwitchCase {
					test: undefined
					leadingComments: Array ["0"]
					loc: Object {
						filename: "comments/basic/switch-function-call-no-semicolon/input.js"
						end: Object {
							column: 10
							line: 6
						}
						start: Object {
							column: 2
							line: 5
						}
					}
					consequent: Array [
						JSBreakStatement {
							label: undefined
							leadingComments: undefined
							loc: Object {
								filename: "comments/basic/switch-function-call-no-semicolon/input.js"
								end: Object {
									column: 10
									line: 6
								}
								start: Object {
									column: 4
									line: 6
								}
							}
						}
					]
				}
			]
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
