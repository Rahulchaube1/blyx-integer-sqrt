# Integer Sqrt

![Package logo](https://github.com/Rahulchaube1/blyx-integer-sqrt/raw/v0.1.1/editor/icon.png)

Return the exact floor of the square root of a nonnegative integer using division-safe binary search.

Scientific and numerical methods · library · 0.1.1

## Function

```blyx
pub fn integer_sqrt(number: i64) -> i64
```

Use finite numeric values. Integer arithmetic assumes that intermediate results fit signed 64-bit storage. All indices are zero-based unless the contract above states otherwise.

| Inputs in declaration order | Expected result |
|---|---|
| `26` | `5` |
| `1` | `1` |
| `-1` | `-1` |

## Run this checkout

Run `blyxc native-run main.blyx` to reproduce `expected.txt`. Run `blyxc native-run checks.blyx` and compare the complete output with `checks-expected.txt`.

## Try the published project

```sh
nest demo integer_sqrt@0.1.1
blyxc native-run integer_sqrt-demo/main.blyx
```

Install with `nest add integer_sqrt@0.1.1` and import `vendor::integer_sqrt::integer_sqrt`.

Maintained by Rahul Chaube. [Blyx](https://www.blyx-lang.space) · [GitHub](https://github.com/Rahulchaube1) · [LinkedIn](https://www.linkedin.com/in/rahulchaube1) · [Sponsor](https://github.com/sponsors/Rahulchaube1)


## Editor snippets

Use this extension with the Blyx Language extension. In a .blyx file, type one of the following prefixes and invoke editor completion.

- `integer_sqrt`
- `use_integer_sqrt`
