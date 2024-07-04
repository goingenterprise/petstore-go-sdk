<!-- Start SDK Example Usage [usage] -->
```go
package main

import (
	"context"
	petstoregosdk "github.com/goingenterprise/petstore-go-sdk"
	"log"
)

func main() {
	s := petstoregosdk.New()
	var limit *int = petstoregosdk.Int(21453)
	ctx := context.Background()
	res, err := s.Pets.ListPets(ctx, limit)
	if err != nil {
		log.Fatal(err)
	}
	if res.Pets != nil {
		// handle response
	}
}

```
<!-- End SDK Example Usage [usage] -->