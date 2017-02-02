# rug-demo

Evolving maven project from junit4 to junit5.

Current project has two editors:

* [AddJUnit5MavenConfig](https://github.com/eddumelendez/rug-demo/blob/master/.atomist/editors/AddJUnit5MavenConfig.rug)
* [AddJUnit5JavaFiles](https://github.com/eddumelendez/rug-demo/blob/master/.atomist/editors/AddJUnit5JavaFiles.rug)

In order to apply `JUnit5`'s changes, run the following commands:

```
rug edit eddumelendez:junit5-rugs:AddJUnit5MavenConfig -l -a 0.1.0
rug edit eddumelendez:junit5-rugs:AddJUnit5JavaFiles -l -a 0.1.0
```