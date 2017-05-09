# goyacc-sample

As of 1.8, 'go tool yacc' is no longer included. Instead, obtain 'goyacc' with the following:  
```go get -u golang.org/x/tools/cmd/goyacc``` 
 
 
Followed by:  
```goyacc -o calc.go -p Calc calc.y``` 
 
 
References: 
https://github.com/golang-samples/yacc/tree/master/simple  
https://godoc.org/github.com/cznic/goyacc  
https://blog.golang.org/generate (outdated)  


