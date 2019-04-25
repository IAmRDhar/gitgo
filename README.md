# GitGo
A minimal CLI app to query GitHub users.

## Installation
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
    $ gitfetch -u IAmRDhar
    ```

- Multi-User Query:

    ```
    $ gitgo -u IAmRDhar,XYZ                                                                                                                                    
    ```

