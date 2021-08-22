# tlv_encoding
 type-length-value encoding
 
 TLV uses fixed sized bytes to determine the specific Type and the size.
 
 the value is then dynamic.

 go test -v 
 ```
 === RUN   TestPayloads
     types_test.go:54: [*main.Binary] "The Cake is a lie"
     types_test.go:54: [*main.String] "Errors are values"
     types_test.go:54: [*main.Binary] "Have you tried turning if off and on again ?"
 --- PASS: TestPayloads (0.00s)
	 PASS
 ok    /Github/tlv_encoding   0.325s
```

from Networking Programming with Go
