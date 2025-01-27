# jlox

## compile and run
Compile: 
```shell
    $ javac -d ./out src/com/craftinginterpreters/lox/*.java
```

Run on prompt:
```shell
    $ java -cp out com.craftinginterpreters.lox.Lox
```

Run file: 
```shell
    $ java -cp out com.craftinginterpreters.lox.Lox examples/calculator.lox
```

Compile GenerateAST: 
```shell
    $ javac -d ./out src/com/craftinginterpreters/tool/*.java
```

Run GenerateAST:
```shell
    $ java -cp out com.craftinginterpreters.tool.GenerateAst ./src/com/craftinginterpreters/lox
```
