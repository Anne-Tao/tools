# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > import > import-default-id-type`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/import/import-default-id-type/input.ts"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/import/import-default-id-type/input.ts"
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
		JSImportDeclaration {
			importKind: undefined
			namedSpecifiers: Array []
			namespaceSpecifier: undefined
			loc: Object {
				filename: "typescript/import/import-default-id-type/input.ts"
				end: Object {
					column: 23
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			source: JSStringLiteral {
				value: "foo"
				loc: Object {
					filename: "typescript/import/import-default-id-type/input.ts"
					end: Object {
						column: 22
						line: 1
					}
					start: Object {
						column: 17
						line: 1
					}
				}
			}
			defaultSpecifier: JSImportDefaultSpecifier {
				loc: Object {
					filename: "typescript/import/import-default-id-type/input.ts"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				local: JSImportSpecifierLocal {
					name: JSBindingIdentifier {
						name: "type"
						loc: Object {
							filename: "typescript/import/import-default-id-type/input.ts"
							identifierName: "type"
							end: Object {
								column: 11
								line: 1
							}
							start: Object {
								column: 7
								line: 1
							}
						}
					}
					importKind: undefined
					loc: Object {
						filename: "typescript/import/import-default-id-type/input.ts"
						end: Object {
							column: 11
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
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
