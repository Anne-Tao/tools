# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > parameter-properties-binding-patterns`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
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
				message: RAW_MARKUP {value: "A parameter property may not be declared using a binding pattern."}
			}
			location: Object {
				filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 16
					line: 2
				}
				start: Object {
					column: 16
					line: 2
				}
			}
		}
	]
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: Object {
					filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
					identifierName: "C"
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
				filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
				end: Object {
					column: 1
					line: 3
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "constructor"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "constructor"
								loc: Object {
									filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
									identifierName: "constructor"
									end: Object {
										column: 15
										line: 2
									}
									start: Object {
										column: 4
										line: 2
									}
								}
							}
							loc: Object {
								filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
								end: Object {
									column: 15
									line: 2
								}
								start: Object {
									column: 4
									line: 2
								}
							}
						}
						loc: Object {
							filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
							end: Object {
								column: 29
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
								filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
								end: Object {
									column: 29
									line: 2
								}
								start: Object {
									column: 27
									line: 2
								}
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
								line: 2
							}
							loc: Object {
								filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
								end: Object {
									column: 15
									line: 2
								}
								start: Object {
									column: 4
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
								filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
								end: Object {
									column: 26
									line: 2
								}
								start: Object {
									column: 15
									line: 2
								}
							}
							params: Array [
								JSBindingArrayPattern {
									elements: Array []
									rest: undefined
									loc: Object {
										filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
										end: Object {
											column: 25
											line: 2
										}
										start: Object {
											column: 16
											line: 2
										}
									}
									meta: JSPatternMeta {
										accessibility: "public"
										readonly: false
										typeAnnotation: undefined
										loc: Object {
											filename: "typescript/class/parameter-properties-binding-patterns/input.ts"
											end: Object {
												column: 25
												line: 2
											}
											start: Object {
												column: 16
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
```

### `diagnostics`

```

 typescript/class/parameter-properties-binding-patterns/input.ts:2:16 parse(js) ━━━━━━━━━━━━━━━━━━━━

  ✖ A parameter property may not be declared using a binding pattern.

    1 │ class C {
  > 2 │     constructor(public []) {}
      │                 ^
    3 │ }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
