# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > optional-async-error`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "typescript/class/optional-async-error/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "typescript/class/optional-async-error/input.js"
		end: Object {
			column: 1
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
				message: Array [
					RAW_MARKUP {value: "Expected "}
					"ts"
					RAW_MARKUP {value: " syntax to be enabled"}
				]
			}
			location: Object {
				filename: "typescript/class/optional-async-error/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 9
					line: 3
				}
				start: Object {
					column: 9
					line: 3
				}
			}
		}
	]
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "B"
				loc: Object {
					filename: "typescript/class/optional-async-error/input.js"
					identifierName: "B"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "typescript/class/optional-async-error/input.js"
				end: Object {
					column: 11
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				body: Array []
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "typescript/class/optional-async-error/input.js"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
			}
		}
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "typescript/class/optional-async-error/input.js"
					identifierName: "A"
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
				filename: "typescript/class/optional-async-error/input.js"
				end: Object {
					column: 1
					line: 4
				}
				start: Object {
					column: 0
					line: 2
				}
			}
			meta: JSClassHead {
				implements: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "typescript/class/optional-async-error/input.js"
					end: Object {
						column: 1
						line: 4
					}
					start: Object {
						column: 0
						line: 2
					}
				}
				superClass: JSReferenceIdentifier {
					name: "B"
					loc: Object {
						filename: "typescript/class/optional-async-error/input.js"
						identifierName: "B"
						end: Object {
							column: 17
							line: 2
						}
						start: Object {
							column: 16
							line: 2
						}
					}
				}
				body: Array [
					TSDeclareMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "method"
								loc: Object {
									filename: "typescript/class/optional-async-error/input.js"
									identifierName: "method"
									end: Object {
										column: 17
										line: 3
									}
									start: Object {
										column: 11
										line: 3
									}
								}
							}
							loc: Object {
								filename: "typescript/class/optional-async-error/input.js"
								end: Object {
									column: 17
									line: 3
								}
								start: Object {
									column: 11
									line: 3
								}
							}
						}
						body: undefined
						loc: Object {
							filename: "typescript/class/optional-async-error/input.js"
							end: Object {
								column: 46
								line: 3
							}
							start: Object {
								column: 4
								line: 3
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								line: 3
							}
							loc: Object {
								filename: "typescript/class/optional-async-error/input.js"
								end: Object {
									column: 17
									line: 3
								}
								start: Object {
									column: 4
									line: 3
								}
							}
						}
						head: JSFunctionHead {
							async: true
							generator: false
							hasHoistedVars: false
							rest: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "typescript/class/optional-async-error/input.js"
								end: Object {
									column: 45
									line: 3
								}
								start: Object {
									column: 17
									line: 3
								}
							}
							params: Array [
								JSBindingIdentifier {
									name: "val"
									loc: Object {
										filename: "typescript/class/optional-async-error/input.js"
										identifierName: "val"
										end: Object {
											column: 21
											line: 3
										}
										start: Object {
											column: 18
											line: 3
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										loc: Object {
											filename: "typescript/class/optional-async-error/input.js"
											end: Object {
												column: 29
												line: 3
											}
											start: Object {
												column: 18
												line: 3
											}
										}
										typeAnnotation: TSStringKeywordTypeAnnotation {
											loc: Object {
												filename: "typescript/class/optional-async-error/input.js"
												end: Object {
													column: 29
													line: 3
												}
												start: Object {
													column: 23
													line: 3
												}
											}
										}
									}
								}
							]
							returnType: TSTypeReference {
								loc: Object {
									filename: "typescript/class/optional-async-error/input.js"
									end: Object {
										column: 45
										line: 3
									}
									start: Object {
										column: 32
										line: 3
									}
								}
								typeName: JSReferenceIdentifier {
									name: "Promise"
									loc: Object {
										filename: "typescript/class/optional-async-error/input.js"
										identifierName: "Promise"
										end: Object {
											column: 39
											line: 3
										}
										start: Object {
											column: 32
											line: 3
										}
									}
								}
								typeParameters: TSTypeParameterInstantiation {
									loc: Object {
										filename: "typescript/class/optional-async-error/input.js"
										end: Object {
											column: 45
											line: 3
										}
										start: Object {
											column: 39
											line: 3
										}
									}
									params: Array [
										TSVoidKeywordTypeAnnotation {
											loc: Object {
												filename: "typescript/class/optional-async-error/input.js"
												end: Object {
													column: 44
													line: 3
												}
												start: Object {
													column: 40
													line: 3
												}
											}
										}
									]
								}
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

 typescript/class/optional-async-error/input.js:3:9 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected ts syntax to be enabled

    1 │ class B { }
    2 │ class A extends B {
  > 3 │     async? method(val: string): Promise<void>;
      │          ^
    4 │ }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
