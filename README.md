# GitGo
A minimal CLI app to query GitHub users.

## Installation
- `cd {$GOPATH}/src/github.com/{YOUR-GITHUB-USERNAME}/gitgo`
- `go install`

## Usage
- Help:

    ```
    $ gitgo
    Usage: gitgo [options]
    Options:
        -u, --user string
            Search Users
    ```  

- Single User Query:

    ```
    $ gitgo -u IAmRDhar
    $ gitgo --user=IAmRDhar,XYZ
    ```

- Multi-User Query:

    ```
    $ gitgo -u IAmRDhar,XYZ                                                                                                                                    
    ```

