# Tic Tac Toe 

### Installing GHC 
Stack will install the correct version of GHC for our project. This is cool because everyone working on your project will be on the same version. Let’s give it a shot: run this in your project folder
```
$ stack setup
```
Which results in:
```
Downloaded lts-3.1 build plan.    
Caching build plan
Fetched package index.
Populated index cache.
Downloaded ghc-7.10.2.
Installed GHC.
stack will use a locally installed GHC
For more information on paths, see 'stack path' and 'stack exec env'
To use this GHC and packages outside of a project, consider using:
stack ghc, stack ghci, stack runghc, or stack exec
```

### Usage 

```
$ stack ghci
Configuring GHCi with the following packages: my-project
GHCi, version 7.10.2: http://www.haskell.org/ghc/  :? for help
Prelude>
```

Load the main module : 
```
Prelude> :load Main
[1 of 1] Compiling Main             ( src/Main.hs, interpreted )
Ok, modules loaded: Main.
```

Run the program by typing `main`: 
```
Main> main
hello world
```

