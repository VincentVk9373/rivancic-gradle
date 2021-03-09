# Gradle build tool example projects

This repository contains examples of various Gradle features structured in modules

|    Module     |  Description  |  Resources   |
| ------------- |:-------------:|-------------:|
| **tasks**     | Implementation of two Gradle tasks which can modify files in specific directory | Task resource  |
| **script-plugin** | Same tasks that are implemented are extracted to script plugin. The easiest way of extracting tasks. | Script plugin resource |
| **buildSrc**  | Tasks extracted to precompiled script plugin. They are written in Gradle script files. They are compiled into class files. | [Gradle Precompile Script Plugin User-guide](https://docs.gradle.org/current/userguide/custom_plugins.html#sec:precompiled_plugins) |
| **apply-precompiled-script-plugin** | An example of applying precompiled plugin to a module | [Gradle Precompile Script Plugin User-guide](https://docs.gradle.org/current/userguide/custom_plugins.html#sec:precompiled_plugins) | 


**Precompiled plugin resources**

https://docs.gradle.org/current/samples/sample_convention_plugins.html
https://docs.gradle.org/current/userguide/custom_plugins.html
https://docs.gradle.org/current/userguide/organizing_gradle_projects.html#organizing_gradle_projects