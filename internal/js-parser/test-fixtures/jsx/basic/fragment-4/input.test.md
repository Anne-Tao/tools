# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > basic > fragment-4`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "jsx/basic/fragment-4/input.jsx"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array ["jsx"]
	loc: Object {
		filename: "jsx/basic/fragment-4/input.jsx"
		end: Object {
			column: 0
			line: 8
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "jsx/basic/fragment-4/input.jsx"
				end: Object {
					column: 3
					line: 7
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSXFragment {
				loc: Object {
					filename: "jsx/basic/fragment-4/input.jsx"
					end: Object {
						column: 3
						line: 7
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				children: Array [
					JSXText {
						value: "\n  "
						loc: Object {
							filename: "jsx/basic/fragment-4/input.jsx"
							end: Object {
								column: 2
								line: 2
							}
							start: Object {
								column: 2
								line: 1
							}
						}
					}
					JSXFragment {
						loc: Object {
							filename: "jsx/basic/fragment-4/input.jsx"
							end: Object {
								column: 5
								line: 6
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						children: Array [
							JSXText {
								value: "\n    "
								loc: Object {
									filename: "jsx/basic/fragment-4/input.jsx"
									end: Object {
										column: 4
										line: 3
									}
									start: Object {
										column: 4
										line: 2
									}
								}
							}
							JSXFragment {
								loc: Object {
									filename: "jsx/basic/fragment-4/input.jsx"
									end: Object {
										column: 7
										line: 5
									}
									start: Object {
										column: 4
										line: 3
									}
								}
								children: Array [
									JSXText {
										value: "\n      super deep\n    "
										loc: Object {
											filename: "jsx/basic/fragment-4/input.jsx"
											end: Object {
												column: 4
												line: 5
											}
											start: Object {
												column: 6
												line: 3
											}
										}
									}
								]
							}
							JSXText {
								value: "\n  "
								loc: Object {
									filename: "jsx/basic/fragment-4/input.jsx"
									end: Object {
										column: 2
										line: 6
									}
									start: Object {
										column: 7
										line: 5
									}
								}
							}
						]
					}
					JSXText {
						value: "\n"
						loc: Object {
							filename: "jsx/basic/fragment-4/input.jsx"
							end: Object {
								column: 0
								line: 7
							}
							start: Object {
								column: 5
								line: 6
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
