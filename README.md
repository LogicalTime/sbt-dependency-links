# sbt-dependency-links
links to dependencies needed by some sbt plugins


https://bintray.com/sbt/sbt-plugin-releases

Maven Dependencies
### addSbtPlugin("org.brianmckenna" % "sbt-wartremover" % "0.14")
http://central.maven.org/maven2/org/brianmckenna/sbt-wartremover_2.10_0.13/0.14/sbt-wartremover-0.14.jar
(no dependency)
### addSbtPlugin("org.scalastyle" %% "scalastyle-sbt-plugin" % "0.8.0")
http://central.maven.org/maven2/org/scalastyle/scalastyle-sbt-plugin_2.10_0.13/0.8.0/scalastyle-sbt-plugin-0.8.0.jar
(need dep)
http://central.maven.org/maven2/org/scalastyle/scalastyle_2.10/0.8.0/scalastyle_2.10-0.8.0.jar
http://central.maven.org/maven2/org/scalastyle/scalastyle_2.10/0.8.0/scalastyle_2.10-0.8.0.pom
http://central.maven.org/maven2/org/scalariform/scalariform_2.10/0.1.7/scalariform_2.10-0.1.7.jar
http://central.maven.org/maven2/org/scalariform/scalariform_2.10/0.1.8/scalariform_2.10-0.1.8.jar
### addSbtPlugin("net.virtual-void" % "sbt-dependency-graph" % "0.8.2")
http://central.maven.org/maven2/net/virtual-void/sbt-dependency-graph_2.10_0.13/0.8.2/sbt-dependency-graph-0.8.2.jar
### addSbtPlugin("org.scoverage" % "sbt-scoverage" % "1.3.5")
http://central.maven.org/maven2/org/scoverage/sbt-scoverage_2.10_0.13/1.3.5/sbt-scoverage-1.3.5.jar
(got this dep)
http://central.maven.org/maven2/org/scoverage/scalac-scoverage-plugin_2.10/1.1.1/scalac-scoverage-plugin_2.10-1.1.1.jar
### addSbtPlugin("org.scalariform" % "sbt-scalariform" % "1.6.0")
http://central.maven.org/maven2/org/scalariform/sbt-scalariform_2.10_0.13/1.6.0/sbt-scalariform-1.6.0.jar
(need dep)
http://central.maven.org/maven2/org/scalariform/scalariform_2.10/0.1.8/scalariform_2.10-0.1.8.jar

For sbt-git:
http://central.maven.org/maven2/org/eclipse/jgit/org.eclipse.jgit.pgm/3.7.0.201502260915-r/org.eclipse.jgit.pgm-3.7.0.201502260915-r.jar

### addSbtPlugin("com.github.mpeltonen" % "sbt-idea" % "1.6.0")
https://dl.bintray.com/sbt/sbt-plugin-releases/com.hanhuy.sbt/sbt-idea/scala_2.10/sbt_0.13/1.6.0/jars/sbt-idea.jar
(have already)### addSbtPlugin("com.typesafe.sbteclipse" % "sbteclipse-plugin" % "4.0.0")
https://dl.bintray.com/sbt/sbt-plugin-releases/com.typesafe.sbteclipse/sbteclipse-plugin/scala_2.10/sbt_0.13/4.0.0/jars/sbteclipse-plugin.jar
### addSbtPlugin("com.eed3si9n" % "sbt-assembly" % "0.14.2")
https://dl.bintray.com/eed3si9n/sbt-plugins/com.eed3si9n/sbt-assembly/scala_2.10/sbt_0.13/0.14.2/jars/sbt-assembly.jar
http://central.maven.org/maven2/org/scalactic/scalactic_2.10/2.2.1/scalactic_2.10-2.2.1.jar
### addSbtPlugin("io.spray" % "sbt-revolver" % "0.8.0")
https://dl.bintray.com/jrudolph/sbt-plugins/io.spray/sbt-revolver/scala_2.10/sbt_0.13/0.8.0/jars/sbt-revolver.jar
### addSbtPlugin("com.earldouglas" % "xsbt-web-plugin" % "2.1.0")
https://dl.bintray.com/earldouglas/sbt-plugins/com.earldouglas/xsbt-web-plugin/scala_2.10/sbt_0.13/2.1.0/jars/xsbt-web-plugin.jar
### addSbtPlugin("com.sksamuel.sbt-versions" % "sbt-versions" % "0.2.0")
https://dl.bintray.com/sbt/sbt-plugin-releases/com.sksamuel.sbt-versions/sbt-versions/scala_2.10/sbt_0.13/0.2.0/jars/sbt-versions.jar
### addSbtPlugin("com.timushev.sbt" % "sbt-updates" % "0.1.10")
https://dl.bintray.com/rtimush/sbt-plugins/com.timushev.sbt/sbt-updates/scala_2.10/sbt_0.13/0.1.10/jars/sbt-updates.jar
### addSbtPlugin("com.typesafe.sbt" % "sbt-git" % "0.8.5")
https://dl.bintray.com/jsuereth/sbt-plugins/com.typesafe.sbt/sbt-git/scala_2.10/sbt_0.13/0.8.5/jars/sbt-git.jar
(maven dep) http://central.maven.org/maven2/org/eclipse/jgit/org.eclipse.jgit.pgm/3.7.0.201502260915-r/org.eclipse.jgit.pgm-3.7.0.201502260915-r.jar
### addSbtPlugin("de.johoop" % "jacoco4sbt" % "2.1.6")
https://dl.bintray.com/sbt/sbt-plugin-releases/de.johoop/jacoco4sbt/scala_2.10/sbt_0.13/2.1.6/jars/jacoco4sbt.jar

### addSbtPlugin("com.jsuereth" % "sbt-pgp" % "1.0.0")
https://dl.bintray.com/sbt/sbt-plugin-releases/com.jsuereth/sbt-pgp/scala_2.10/sbt_0.13/1.0.0/jars/sbt-pgp.jar
https://dl.bintray.com/sbt/sbt-plugin-releases/com.jsuereth/pgp-library/scala_2.10/sbt_0.13/1.0.0/jars/pgp-library.jar
<dependency name="dispatch-http_2.10" conf="compile->default(compile)" rev="0.8.10" org="net.databinder"/>
### addSbtPlugin("com.github.gseitz" % "sbt-release" % "1.0.2")
https://dl.bintray.com/sbt/sbt-plugin-releases/com.github.gseitz/sbt-release/scala_2.10/sbt_0.13/1.0.3/jars/sbt-release.jar
### addSbtPlugin("com.artima.supersafe" % "sbtplugin" % "1.1.0-RC6")
http://repo.artima.com/releases/com/artima/supersafe/sbtplugin_2.10_0.13/1.1.0-RC6/sbtplugin-1.1.0-RC6.jar
resolvers += "Artima Maven Repository" at "http://repo.artima.com/releases"
http://central.maven.org/maven2/org/scalactic/scalactic_2.10/2.2.1/scalactic_2.10-2.2.1.jar
http://central.maven.org/maven2/org/scalactic/scalactic_2.10/2.2.6/scalactic_2.10-2.2.6.jar
http://central.maven.org/maven2/org/scalactic/scalactic_2.11/2.2.6/scalactic_2.11-2.2.6.jar
http://central.maven.org/maven2/org/scalactic/scalactic_2.11/3.0.0-M15/scalactic_2.11-3.0.0-M15.jar
