# sbt-musical

NO MUSIC, NO BUILD. Enjoy your compile time.

## Install

 1. Buy Mac. (Sorry...)
 2. Install bash-itunes

```
$ mkdir ~/bin; curl https://raw.github.com/illusori/bash-itunes/master/itunes > ~/bin/itunes && chmod 0755 !#:3
```

 3. In your ~/.sbt/plugins/build.sbt

```scala
addSbtPlugin("com.github.tototoshi" % "sbt-musical" % "0.1.0")
```

## Usage

First, open iTunes.

Prefix arbitrary commands with ♪. This play music while executing the command.

```
> ♪ compile
```

```
> ♪ test
```


## License

Creative Commons Attribution-Share Alike 2.0 UK: England &amp; Wales License
http://creativecommons.org/licenses/by-sa/2.0/uk/