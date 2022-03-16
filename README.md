# Raghavendra Reddy

## Steps to run the word count
1   Install go from [Go](https://go.dev/learn/)
2   Check the go version using the command: go version
3   Get the apache beam go sdk using the command:
    ```go get -u github.com/apache/beam/sdks/v2/go/pkg/beam```
4   Install the wordcount example using the command:
    ```go install github.com/apache/beam/sdks/v2/go/examples/wordcount```
5   Create a wordcount.go file and add the code from wordcount example from [example](https://github.com/apache/beam/tree/master/sdks/go/examples/wordcount
)
6   Run the wordcount example using the command:
    ```go run wordcount.go --input <input file> --output <output file>```
7   If you encounter any error run the below command and rerun the step 6 command:
    ```go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0```


