# GitGo
A minimal CLI app to query GitHub users.

## Installation
- `go install`

## Usage
- Help:

    ```
    $ $GOBIN/gitgo
    Usage: gitgo [options]
    Options:
        -u, --user string
            Search Users
    ```  

- Single User Query:

    ```
    $ gitgo -u IAmRDhar
    $ gitgo --user=IAmRDhar
    ```

- Multi-User Query:

    ```
    $ gitgo -u IAmRDhar,XYZ    
    $ gitgo --user=IAmRDhar,XYZ
    ```

