# jlox

## compile and run
Compile: 
```sh
$ javac -d ./out src/com/craftinginterpreters/lox/*.java
```

Run on prompt:
```sh
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
```sh
$ java -cp out com.craftinginterpreters.lox.Lox examples/calculator.lox
```
