# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-object-initialiser > invalid-proto-setter-literal-identifier`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 62
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
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Redefinition of __proto__ property'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 51
          index: 51
          line: 1
        }
        start: Object {
          column: 42
          index: 42
          line: 1
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 61
          index: 61
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: ObjectExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 60
            index: 60
            line: 1
          }
          start: Object {
            column: 1
            index: 1
            line: 1
          }
        }
        properties: Array [
          ObjectMethod {
            kind: 'set'
            key: StaticPropertyKey {
              value: Identifier {
                name: '__proto__'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 16
                    index: 16
                    line: 1
                  }
                  start: Object {
                    column: 7
                    index: 7
                    line: 1
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 16
                  index: 16
                  line: 1
                }
                start: Object {
                  column: 7
                  index: 7
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 21
                index: 21
                line: 1
              }
              start: Object {
                column: 3
                index: 3
                line: 1
              }
            }
            body: BlockStatement {
              body: Array []
              directives: Array []
              loc: Object {
                filename: 'input.js'
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
            head: FunctionHead {
              async: false
              generator: false
              hasHoistedVars: false
              predicate: undefined
              rest: undefined
              returnType: undefined
              thisType: undefined
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 19
                  index: 19
                  line: 1
                }
                start: Object {
                  column: 16
                  index: 16
                  line: 1
                }
              }
              params: Array [
                BindingIdentifier {
                  name: 'x'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 18
                      index: 18
                      line: 1
                    }
                    start: Object {
                      column: 17
                      index: 17
                      line: 1
                    }
                  }
                  meta: PatternMeta {
                    optional: undefined
                    typeAnnotation: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 18
                        index: 18
                        line: 1
                      }
                      start: Object {
                        column: 17
                        index: 17
                        line: 1
                      }
                    }
                  }
                }
              ]
            }
          }
          ObjectProperty {
            key: StaticPropertyKey {
              value: StringLiteral {
                value: '__proto__'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 34
                    index: 34
                    line: 1
                  }
                  start: Object {
                    column: 23
                    index: 23
                    line: 1
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 34
                  index: 34
                  line: 1
                }
                start: Object {
                  column: 23
                  index: 23
                  line: 1
                }
              }
            }
            value: NullLiteral {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 40
                  index: 40
                  line: 1
                }
                start: Object {
                  column: 36
                  index: 36
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 40
                index: 40
                line: 1
              }
              start: Object {
                column: 23
                index: 23
                line: 1
              }
            }
          }
          ObjectProperty {
            key: StaticPropertyKey {
              value: Identifier {
                name: '__proto__'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 51
                    index: 51
                    line: 1
                  }
                  start: Object {
                    column: 42
                    index: 42
                    line: 1
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 51
                  index: 51
                  line: 1
                }
                start: Object {
                  column: 42
                  index: 42
                  line: 1
                }
              }
            }
            value: NullLiteral {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 57
                  index: 57
                  line: 1
                }
                start: Object {
                  column: 53
                  index: 53
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 57
                index: 57
                line: 1
              }
              start: Object {
                column: 42
                index: 42
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