title: Empezando con liftweb
date: 2013-04-17

# Instalando homebrew

En el caso de **OSX** una forma sencilla de instalar [sbt](http://www.scala-sbt.org/),  [MongoDB](http://www.mongodb.org/)  y otros es instalar [homebrew](http://mxcl.github.io/homebrew/) con el comando `ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"`

### Instalando SBT

Para poder usar liftweb tienes que instalar [sbt](http://www.scala-sbt.org/) (también se puede usar [maven](https://www.assembla.com/wiki/show/liftweb/Using_Maven) yo he escogido usar [sbt](http://www.scala-sbt.org/) instalalo mediante `brew install sbt`


### Instalando MongoDB
También puedes instalar [MongoDB](http://www.mongodb.org) via `brew install mongodb` y puede que te guste el control desde el panel de preferencias [mongodb-macosx-prefspane](https://github.com/remysaissy/mongodb-macosx-prefspane) [[download]](https://github.com/remysaissy/mongodb-macosx-prefspane/raw/master/download/MongoDB.prefPane.zip) o simplemente [ejecutar mongoDB al iniciar mediante un plist](http://hunterford.me/mongodb-startup-item/).

Necesitas tener [XCode](https://developer.apple.com/xcode/) de antemano y haberlo abierto una vez para aceptar los terminos o haber ejecutado `

    Builds will fail! Agree to the license by opening Xcode.app or running:
    xcodebuild -license

Y se puede ejecutar inmediatemente `mongod`.

Comprobar que todo este corriendo correctamente accediendo a [http://localhost:28017/](http://localhost:28017/)

#### interfaces para mongodb

[Admin UIs](http://docs.mongodb.org/ecosystem/tools/administration-interfaces/) o [Mongo Interface@stackexchange](http://stackoverflow.com/questions/4269688/mongo-interface) 

Puedes descargar [mongohub](http://mongohub.todayclose.com/) o el mismo desde github [Mongo hub mac](https://github.com/fotonauts/MongoHub-Mac).

O una con un rango probablemente más amplio [Induction](http://inductionapp.com/)

Puedes ver el log mediante `tail -f /usr/local/var/log/mongodb/mongo.log`
# scala-ide

Aunque hay un plugin de scala para [eclipse](http://www.eclipse.org) hay una versión que es [stand alone de Typesafe](http://typesafe.com/stack/downloads/scala-ide) esta versión permite no tocar tu Eclipse.

> NOTA: Hay que tener cuidado con la versión de scala a usar que corresponda al IDE (hay dos versiones, la más reciente es 2.10 a este momento).

### Instalando ScalaTest plugin

En el menu Window->Install new Software->


# Siguiendo el cookbook
Pues lo siguiente que hay que hacer es empezar con el [cookbook](http://cookbook.liftweb.net/#LiftFromScratch) a este le tienes que agregar como _hacer un template_ para que aparezca el menu.

# Otras referencias pueden ser:

#### Para scala

* [Simply scala](http://www.simplyscala.com/) online REPL
* [Try scala](http://www.tryscala.com/) online REPL
* [progfun](https://www.coursera.org/course/progfun)
* [scala school](http://twitter.github.io/scala_school/)
* scala official
  * [scala docs](http://docs.scala-lang.org/)
  * [scala tutorials](http://docs.scala-lang.org/tutorials/)
  * [scala style guide](http://docs.scala-lang.org/style/)
  * [scala cheatsheets](http://docs.scala-lang.org/cheatsheets/)
  * [scala glossary](http://docs.scala-lang.org/glossary/)
  * [scala API](http://www.scala-lang.org/api/current/index.html#package)
  * [scala tour](http://docs.scala-lang.org/tutorials/tour/tour-of-scala.html)
* [scala wiki@stackoverflow](http://stackoverflow.com/tags/scala/info)

#### Para mongo

* [Try mongo](http://try.mongodb.org/) online REPL