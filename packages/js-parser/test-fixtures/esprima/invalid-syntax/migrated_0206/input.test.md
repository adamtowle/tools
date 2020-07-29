# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0206`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "esprima/invalid-syntax/migrated_0206/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/invalid-syntax/migrated_0206/input.js"
		end: Object {
			column: 0
			index: 42
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						"arguments"
						RAW_MARKUP {value: " is a reserved word"}
					]
				}
			}
			location: Object {
				filename: "esprima/invalid-syntax/migrated_0206/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 19
					index: 19
					line: 1
				}
				start: Object {
					column: 10
					index: 10
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/invalid-syntax/migrated_0206/input.js"
				end: Object {
					column: 41
					index: 41
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSCallExpression {
				arguments: Array []
				loc: Object {
					filename: "esprima/invalid-syntax/migrated_0206/input.js"
					end: Object {
						column: 41
						index: 41
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				callee: JSFunctionExpression {
					id: JSBindingIdentifier {
						name: "arguments"
						loc: Object {
							filename: "esprima/invalid-syntax/migrated_0206/input.js"
							identifierName: "arguments"
							end: Object {
								column: 19
								index: 19
								line: 1
							}
							start: Object {
								column: 10
								index: 10
								line: 1
							}
						}
					}
					loc: Object {
						filename: "esprima/invalid-syntax/migrated_0206/input.js"
						end: Object {
							column: 38
							index: 38
							line: 1
						}
						start: Object {
							column: 1
							index: 1
							line: 1
						}
					}
					head: JSFunctionHead {
						async: false
						generator: false
						hasHoistedVars: false
						params: Array []
						rest: undefined
						returnType: undefined
						thisType: undefined
						typeParameters: undefined
						loc: Object {
							filename: "esprima/invalid-syntax/migrated_0206/input.js"
							end: Object {
								column: 21
								index: 21
								line: 1
							}
							start: Object {
								column: 19
								index: 19
								line: 1
							}
						}
					}
					body: JSBlockStatement {
						body: Array []
						loc: Object {
							filename: "esprima/invalid-syntax/migrated_0206/input.js"
							end: Object {
								column: 38
								index: 38
								line: 1
							}
							start: Object {
								column: 22
								index: 22
								line: 1
							}
						}
						directives: Array [
							JSDirective {
								value: "use strict"
								loc: Object {
									filename: "esprima/invalid-syntax/migrated_0206/input.js"
									end: Object {
										column: 36
										index: 36
										line: 1
									}
									start: Object {
										column: 23
										index: 23
										line: 1
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
```

### `diagnostics`

```

 esprima/invalid-syntax/migrated_0206/input.js:1:10 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ arguments is a reserved word

    (function arguments() {'use strict'; })()
              ^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```