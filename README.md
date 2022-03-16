# Raghavendra Reddy

## Steps to run the word count
*   Install go from [Go](https://go.dev/learn/)
*   Check the go version using the command: go version
*   Get the apache beam go sdk using the command:
    ```go get -u github.com/apache/beam/sdks/v2/go/pkg/beam```
*   Install the wordcount example using the command:
    ```go install github.com/apache/beam/sdks/v2/go/examples/wordcount```
*   Create a wordcount.go file and add the code from wordcount example from [example](https://github.com/apache/beam/tree/master/sdks/go/examples/wordcount
)
*   Run the wordcount example using the command:
    ```go run wordcount.go --input <input file> --output <output file>```
*   If you encounter any error run the below command and rerun the step 6 command:
    ```go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0```


