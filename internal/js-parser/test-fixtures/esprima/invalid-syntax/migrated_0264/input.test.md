# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0264`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "esprima/invalid-syntax/migrated_0264/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/invalid-syntax/migrated_0264/input.js"
		end: Object {
			column: 0
			line: 2
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
					RAW_MARKUP {value: "Unexpected token, expected "}
					"{"
				]
			}
			location: Object {
				filename: "esprima/invalid-syntax/migrated_0264/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 19
					line: 1
				}
				start: Object {
					column: 18
					line: 1
				}
			}
		}
	]
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "esprima/invalid-syntax/migrated_0264/input.js"
					identifierName: "A"
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
				filename: "esprima/invalid-syntax/migrated_0264/input.js"
				end: Object {
					column: 24
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "esprima/invalid-syntax/migrated_0264/input.js"
					end: Object {
						column: 24
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				superClass: JSReferenceIdentifier {
					name: "a"
					loc: Object {
						filename: "esprima/invalid-syntax/migrated_0264/input.js"
						identifierName: "a"
						end: Object {
							column: 17
							line: 1
						}
						start: Object {
							column: 16
							line: 1
						}
					}
				}
				body: Array [
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: ""
								loc: Object {
									filename: "esprima/invalid-syntax/migrated_0264/input.js"
									identifierName: ""
									end: Object {
										column: 23
										line: 1
									}
									start: Object {
										column: 22
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/invalid-syntax/migrated_0264/input.js"
								end: Object {
									column: 23
									line: 1
								}
								start: Object {
									column: 22
									line: 1
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "esprima/invalid-syntax/migrated_0264/input.js"
							end: Object {
								column: 23
								line: 1
							}
							start: Object {
								column: 22
								line: 1
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
								column: 22
								line: 1
							}
							loc: Object {
								filename: "esprima/invalid-syntax/migrated_0264/input.js"
								end: Object {
									column: 23
									line: 1
								}
								start: Object {
									column: 22
									line: 1
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

 esprima/invalid-syntax/migrated_0264/input.js:1:18 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unexpected token, expected {

    class A extends a + b {}
                      ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
