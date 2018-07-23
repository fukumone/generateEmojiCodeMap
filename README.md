ejikit
====================

Generate a useful template for emoji

## Install

```bash
$ go get github.com/fukumone/ejikit
```

## Usage

### Create a mapping for emoji

```go
package main

import (
  "github.com/fukumone/ejikit"
)

func main() {
  ejikit.CreateTemplate()
}
```

### Output emoji list

```go
package main

import (
  "github.com/fukumone/ejikit"
)

func main() {
  ejikit.EmojiOutput()
}
```

### Output oneline emoji

```go
package main

import (
  "github.com/fukumone/ejikit"
)

func main() {
  ejikit.OnLineEmojiOutPut()
}
```
