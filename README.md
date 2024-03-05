> [!WARNING]
> This project is working on progress.

# where
Lightweight command to get lines matching specified conditions

# Usage

```txt
where <matcher> [<file>]

matcher:
    A string to match against each line.

file:
    The file to read. If not specified, lines are read from stdin
```


# Examples

```terminal
$ cat data.txt
1 john@example.com   John_Doe
2 sherry@example.com Sherry_Berry
3 ram@example.com    Ram_Singh

$ cat data.txt | where 'f2 == sherry@example.com'
2 sherry@example.com Sherry_Berry
```
