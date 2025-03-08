This repo for tracking dependencies of official slackware-current packages. Mirrored from slackel

How contribute:
* Create a dep file with this filename format:<br>`<slackware package name>.dep`
* Inside the dep file add the package dependencies of that slackware package using this format:<br>`<slackware package name 1>|<slackware package name 2>|<slackware package name 3>`
* For subdependencies use this format: <br>`<slackware package name 1>,<slackware package a>|<slackware package name 2>,<slackware package a>,<slackware package b>`
