# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > module-attributes > incorrect-arity`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "experimental/module-attributes/incorrect-arity/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "experimental/module-attributes/incorrect-arity/input.js"
		end: Object {
			column: 0
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
				message: RAW_MARKUP {value: "import() requires exactly one argument"}
			}
			location: Object {
				filename: "experimental/module-attributes/incorrect-arity/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 7
					line: 1
				}
				start: Object {
					column: 7
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/module-attributes/incorrect-arity/input.js"
				end: Object {
					column: 9
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSImportCall {
				loc: Object {
					filename: "experimental/module-attributes/incorrect-arity/input.js"
					end: Object {
						column: 8
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
				argument: JSReferenceIdentifier {
					name: "INVALID_PLACEHOLDER"
					loc: Object {
						filename: "experimental/module-attributes/incorrect-arity/input.js"
						end: Object {
							column: 7
							line: 1
						}
						start: Object {
							column: 7
							line: 1
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/module-attributes/incorrect-arity/input.js"
				end: Object {
					column: 20
					line: 2
				}
				start: Object {
					column: 0
					line: 2
				}
			}
			expression: JSImportCall {
				loc: Object {
					filename: "experimental/module-attributes/incorrect-arity/input.js"
					end: Object {
						column: 20
						line: 2
					}
					start: Object {
						column: 6
						line: 2
					}
				}
				argument: JSStringLiteral {
					value: "./foo.json"
					loc: Object {
						filename: "experimental/module-attributes/incorrect-arity/input.js"
						end: Object {
							column: 19
							line: 2
						}
						start: Object {
							column: 7
							line: 2
						}
					}
				}
			}
		}
		JSBlockStatement {
			directives: Array []
			loc: Object {
				filename: "experimental/module-attributes/incorrect-arity/input.js"
				end: Object {
					column: 46
					line: 2
				}
				start: Object {
					column: 21
					line: 2
				}
			}
			body: Array [
				JSWithStatement {
					loc: Object {
						filename: "experimental/module-attributes/incorrect-arity/input.js"
						end: Object {
							column: 44
							line: 2
						}
						start: Object {
							column: 23
							line: 2
						}
					}
					object: JSReferenceIdentifier {
						name: "INVALID_PLACEHOLDER"
						loc: Object {
							filename: "experimental/module-attributes/incorrect-arity/input.js"
							end: Object {
								column: 28
								line: 2
							}
							start: Object {
								column: 27
								line: 2
							}
						}
					}
					body: JSBlockStatement {
						directives: Array []
						loc: Object {
							filename: "experimental/module-attributes/incorrect-arity/input.js"
							end: Object {
								column: 44
								line: 2
							}
							start: Object {
								column: 29
								line: 2
							}
						}
						body: Array [
							JSLabeledStatement {
								loc: Object {
									filename: "experimental/module-attributes/incorrect-arity/input.js"
									end: Object {
										column: 43
										line: 2
									}
									start: Object {
										column: 31
										line: 2
									}
								}
								label: JSIdentifier {
									name: "type"
									loc: Object {
										filename: "experimental/module-attributes/incorrect-arity/input.js"
										identifierName: "type"
										end: Object {
											column: 35
											line: 2
										}
										start: Object {
											column: 31
											line: 2
										}
									}
								}
								body: JSExpressionStatement {
									loc: Object {
										filename: "experimental/module-attributes/incorrect-arity/input.js"
										end: Object {
											column: 43
											line: 2
										}
										start: Object {
											column: 37
											line: 2
										}
									}
									expression: JSStringLiteral {
										value: "json"
										loc: Object {
											filename: "experimental/module-attributes/incorrect-arity/input.js"
											end: Object {
												column: 43
												line: 2
											}
											start: Object {
												column: 37
												line: 2
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
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/module-attributes/incorrect-arity/input.js"
				end: Object {
					column: 47
					line: 2
				}
				start: Object {
					column: 46
					line: 2
				}
			}
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "experimental/module-attributes/incorrect-arity/input.js"
					end: Object {
						column: 47
						line: 2
					}
					start: Object {
						column: 46
						line: 2
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/module-attributes/incorrect-arity/input.js"
				end: Object {
					column: 61
					line: 2
				}
				start: Object {
					column: 48
					line: 2
				}
			}
			expression: JSStringLiteral {
				value: "unsupported"
				loc: Object {
					filename: "experimental/module-attributes/incorrect-arity/input.js"
					end: Object {
						column: 61
						line: 2
					}
					start: Object {
						column: 48
						line: 2
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/module-attributes/incorrect-arity/input.js"
				end: Object {
					column: 63
					line: 2
				}
				start: Object {
					column: 61
					line: 2
				}
			}
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "experimental/module-attributes/incorrect-arity/input.js"
					end: Object {
						column: 62
						line: 2
					}
					start: Object {
						column: 61
						line: 2
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```

 experimental/module-attributes/incorrect-arity/input.js:1:7 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ import() requires exactly one argument

  > 1 │ import();
      │        ^
    2 │ import("./foo.json", { with: { type: "json"} }, "unsupported");

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
