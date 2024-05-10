# Go ContentType Package

This package provides a collection of common MIME-type constants. These constants can be used in various contexts, such as setting HTTP response headers, validating file types, and other related scenarios.

## Features

- Provides constants for common MIME types like `application/json`, `text/html`, `image/jpeg`, and more.
- Easy to install and use in other Go projects.

## Installation

To install the package, use the following command:

```shell
go get github.com/skodnik/go-contenttype
```

You can also install a specific version or the latest version using go install:

```shell
go get github.com/skodnik/go-contenttype@latest
```

## Usage

To use the constants in your Go project, import the package and reference the constants by name. Here's an example of how you might use this package to set HTTP response headers:

```go
package main

import (
    "fmt"
    "github.com/skodnik/go-contenttype/contenttype"
)

func main() {
    fmt.Println("Content-Type for JSON:", contenttype.ApplicationJSON)
    fmt.Println("Content-Type for HTML:", contenttype.TextHTML)
    fmt.Println("Content-Type for PNG:", contenttype.ImagePNG)
}
```

## Contributing

Contributions are welcome! If you have suggestions for additional MIME-type constants or other improvements, please open an issue or submit a pull request.

## License

[GNU General Public License v3](LICENSE)

## Disclaimer

The author is not liable for any claims, losses, or other liabilities arising from or related to the use, distribution, or other handling of this software.