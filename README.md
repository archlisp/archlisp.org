# archlisp.org

Install Roswell: https://github.com/roswell/roswell

```
brew install roswell
```

Install Clack: https://github.com/fukamachi/clack

```
ros install clack
```

Add Roswell's binaries to your `$PATH`.

```
export PATH=$PATH:~/.roswell/bin
```

Launch the app.

```
clackup app.lisp
```
