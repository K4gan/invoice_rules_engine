# Invoice Rules Engine

    Invoice rule engine with composable validation checks.

    ## Stack

    - Language: Java
    - Difficulty: medium
    - Scope: small, self-contained service/tool with clear extension points

    ## Project layout

    The repository keeps implementation code under `src/` where that is idiomatic, plus a short runnable entry point and a small sample payload when useful.

    ## Run

    ```bash
    javac src/main/java/dev/portfolio/invoicerulesengine/App.java
java -cp src/main/java dev.portfolio.invoicerulesengine.App
    ```

    ## Engineering notes

    The implementation keeps parsing, domain logic and output formatting separate enough to grow without turning into a script dump. Generated artifacts and dependency folders are intentionally ignored.
