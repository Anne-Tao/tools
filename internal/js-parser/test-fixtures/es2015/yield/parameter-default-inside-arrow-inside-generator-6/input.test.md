# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > parameter-default-inside-arrow-inside-generator-6`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
		end: Object {
			column: 1
			line: 3
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
				message: RAW_MARKUP {value: "yield is not allowed in generator parameters"}
			}
			location: Object {
				filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 13
					line: 2
				}
				start: Object {
					column: 13
					line: 2
				}
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "fn"
				loc: Object {
					filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
					identifierName: "fn"
					end: Object {
						column: 12
						line: 1
					}
					start: Object {
						column: 10
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
				end: Object {
					column: 1
					line: 3
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
					filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
					end: Object {
						column: 14
						line: 1
					}
					start: Object {
						column: 12
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 15
						line: 1
					}
				}
				body: Array [
					JSExpressionStatement {
						loc: Object {
							filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
							end: Object {
								column: 22
								line: 2
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						expression: JSArrowFunctionExpression {
							loc: Object {
								filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
								end: Object {
									column: 21
									line: 2
								}
								start: Object {
									column: 2
									line: 2
								}
							}
							body: JSBlockStatement {
								body: Array []
								directives: Array []
								loc: Object {
									filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
									end: Object {
										column: 21
										line: 2
									}
									start: Object {
										column: 19
										line: 2
									}
								}
							}
							head: JSFunctionHead {
								async: false
								hasHoistedVars: false
								rest: undefined
								returnType: undefined
								thisType: undefined
								loc: Object {
									filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
									end: Object {
										column: 18
										line: 2
									}
									start: Object {
										column: 2
										line: 2
									}
								}
								params: Array [
									JSBindingAssignmentPattern {
										operator: "="
										loc: Object {
											filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
											end: Object {
												column: 14
												line: 2
											}
											start: Object {
												column: 3
												line: 2
											}
										}
										left: JSBindingIdentifier {
											name: "x"
											loc: Object {
												filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
												identifierName: "x"
												end: Object {
													column: 4
													line: 2
												}
												start: Object {
													column: 3
													line: 2
												}
											}
										}
										right: JSYieldExpression {
											argument: undefined
											delegate: false
											loc: Object {
												filename: "es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js"
												end: Object {
													column: 13
													line: 2
												}
												start: Object {
													column: 8
													line: 2
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

 es2015/yield/parameter-default-inside-arrow-inside-generator-6/input.js:2:13 parse(js) ━━━━━━━━━━━━

  ✖ yield is not allowed in generator parameters

    1 │ function* fn() {
  > 2 │   (x = (yield)) => {};
      │              ^
    3 │ }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
