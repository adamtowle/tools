# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-object-pattern > empty-for-lex`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-object-pattern/empty-for-lex/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-object-pattern/empty-for-lex/input.js"
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
		JSForInStatement {
			loc: Object {
				filename: "esprima/es2015-object-pattern/empty-for-lex/input.js"
				end: Object {
					column: 18
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			body: JSEmptyStatement {
				loc: Object {
					filename: "esprima/es2015-object-pattern/empty-for-lex/input.js"
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
			right: JSNumericLiteral {
				value: 0
				format: undefined
				loc: Object {
					filename: "esprima/es2015-object-pattern/empty-for-lex/input.js"
					end: Object {
						column: 16
						line: 1
					}
					start: Object {
						column: 15
						line: 1
					}
				}
			}
			left: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "esprima/es2015-object-pattern/empty-for-lex/input.js"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 5
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingObjectPattern {
							properties: Array []
							rest: undefined
							loc: Object {
								filename: "esprima/es2015-object-pattern/empty-for-lex/input.js"
								end: Object {
									column: 11
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "esprima/es2015-object-pattern/empty-for-lex/input.js"
							end: Object {
								column: 11
								line: 1
							}
							start: Object {
								column: 9
								line: 1
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
