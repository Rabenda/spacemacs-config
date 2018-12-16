# spacemacs-config


## Install

```bash
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
cd ~/.emacs.d/ && git checkout develop && git pull && cd -
git clone https://github.com/Rabenda/spacemacs-config ~/.spacemacs.d
```
## Ensime Install
[ensime install](http://ensime.github.io/build_tools/sbt/#install)

sbt-ensime is an editor integration plugin and isn’t a strict requirement of the build.

Therefore it is recommended to install it as a global plugin so that it’s always available.

To do so, add it to ~/.sbt/1.0/plugins/plugins.sbt (create if necessary) as such:

```scala
addSbtPlugin("org.ensime" % "sbt-ensime" % "2.5.1")
```

Then in order to create the .ensime file for your project, start sbt (in the terminal or your editor’s sbt mode) and run the ensimeConfig command.


## Add major mode

Scala java c-c++
