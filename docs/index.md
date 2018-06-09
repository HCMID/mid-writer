## Writing web pages with executable code


### One-time set up

- [Set up a github repository](setup)

### Writing

The regular cycle involves three steps:

1.  Add content to directory `src/md`.
2.  In an sbt console, run `tutQuick`
3.  Commit your changes.


#### Adding content

Write normal markdown files in the `src/md` directory.  To include executable code, use a fenced-code block (set off with triple back ticks), labelled as a `tut` block.




    Including a block like this:
    ```tut
scala>     val example = "This is a block of Scala code"
example: String = This is a block of Scala code
    ```


will generate this:


```scala
scala> val example = "This is a block of Scala code"
example: String = This is a block of Scala code
```

#### The `tut` plugin


#### Committing your changes
