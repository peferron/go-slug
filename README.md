# slug [![GoDoc](https://godoc.org/github.com/peferron/slug?status.png)](https://godoc.org/github.com/peferron/slug) [![Build Status](https://travis-ci.org/peferron/slug.svg?branch=master)](https://travis-ci.org/peferron/slug) [![Coverage Status](https://coveralls.io/repos/peferron/slug/badge.svg?branch=master)](https://coveralls.io/r/peferron/slug?branch=master)

slug is a Go library for generating URL-friendly [slugs](http://en.wikipedia.org/wiki/Slug_%28web_publishing%29#Slug).

## Examples

Before and after:
- `A Lovely Day` → `a-lovely-day`
- `Living in 北京` → `living-in-bei-jing`

## Usage

```go
package main

import "github.com/peferron/slug"

func main() {
    s := slug.Generate("Hello World")
    print(s) // Prints "hello-world"
}
```

See the full [API reference](https://godoc.org/github.com/peferron/slug).
