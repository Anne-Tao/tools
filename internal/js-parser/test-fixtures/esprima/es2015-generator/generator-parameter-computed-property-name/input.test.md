# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-generator > generator-parameter-computed-property-name`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
		end: Object {
			column: 0
			line: 4
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
				message: RAW_MARKUP {value: "Expected an identifier"}
			}
			location: Object {
				filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 12
					line: 2
				}
				start: Object {
					column: 12
					line: 2
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
				end: Object {
					column: 2
					line: 3
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSFunctionExpression {
				id: undefined
				loc: Object {
					filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 1
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
						filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
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
				body: JSBlockStatement {
					directives: Array []
					loc: Object {
						filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
						end: Object {
							column: 1
							line: 3
						}
						start: Object {
							column: 13
							line: 1
						}
					}
					body: Array [
						JSFunctionDeclaration {
							id: JSBindingIdentifier {
								name: ""
								loc: Object {
									filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
									identifierName: ""
									end: Object {
										column: 13
										line: 2
									}
									start: Object {
										column: 12
										line: 2
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
								end: Object {
									column: 31
									line: 2
								}
								start: Object {
									column: 4
									line: 2
								}
							}
							body: JSBlockStatement {
								body: Array []
								directives: Array []
								loc: Object {
									filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
									end: Object {
										column: 31
										line: 2
									}
									start: Object {
										column: 29
										line: 2
									}
								}
							}
							head: JSFunctionHead {
								async: false
								generator: false
								hasHoistedVars: false
								rest: undefined
								returnType: undefined
								thisType: undefined
								typeParameters: undefined
								loc: Object {
									filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
									end: Object {
										column: 28
										line: 2
									}
									start: Object {
										column: 13
										line: 2
									}
								}
								params: Array [
									JSBindingObjectPattern {
										rest: undefined
										loc: Object {
											filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
											end: Object {
												column: 27
												line: 2
											}
											start: Object {
												column: 13
												line: 2
											}
										}
										meta: JSPatternMeta {
											optional: undefined
											typeAnnotation: undefined
											loc: Object {
												filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
												end: Object {
													column: 27
													line: 2
												}
												start: Object {
													column: 13
													line: 2
												}
											}
										}
										properties: Array [
											JSBindingObjectPatternProperty {
												key: JSStaticPropertyKey {
													value: JSIdentifier {
														name: ""
														loc: Object {
															filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
															identifierName: ""
															end: Object {
																column: 23
																line: 2
															}
															start: Object {
																column: 22
																line: 2
															}
														}
													}
													loc: Object {
														filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
														end: Object {
															column: 23
															line: 2
														}
														start: Object {
															column: 22
															line: 2
														}
													}
												}
												value: JSBindingIdentifier {
													name: "y"
													loc: Object {
														filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
														identifierName: "y"
														end: Object {
															column: 26
															line: 2
														}
														start: Object {
															column: 25
															line: 2
														}
													}
												}
												loc: Object {
													filename: "esprima/es2015-generator/generator-parameter-computed-property-name/input.js"
													end: Object {
														column: 26
														line: 2
													}
													start: Object {
														column: 22
														line: 2
													}
												}
											}
										]
									}
								]
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

 esprima/es2015-generator/generator-parameter-computed-property-name/input.js:2:12 parse(js) ━━━━━━━

  ✖ Expected an identifier

    1 │ (function*() {
  > 2 │     function({[yield 3]: y}) {}
      │             ^
    3 │ })

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
