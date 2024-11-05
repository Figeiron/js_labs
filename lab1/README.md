1. У першому випадку:

    ```html
    <script src="big.js"></script>
    <script src="small.js"></script>
    ```
    першим виконається big.js оскільки написаний першим
##

2. У другому випадку:

    ```html
    <script async src="big.js"></script>
    <script async src="small.js"></script>
    ```
    першим виконається small.js оскільки швидше виконається