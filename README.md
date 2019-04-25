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
    $ $GOBIN/gitgo -u IAmRDhar
    $ $GOBIN/gitgo --user=IAmRDhar
    ```

- Multi-User Query:

    ```
    $ $GOBIN/gitgo -u IAmRDhar,XYZ    
    $ $GOBIN/gitgo --user=IAmRDhar,XYZ
    ```

