```
> Task :sub2:compileJava
Validation failed for task ':sub2:compileJava', disabling optimizations:
  - Task ':sub2:compileJava' uses the output of task ':sub1:bootJar', without declaring an explicit dependency (using Task.dependsOn() or Task.mustRunAfter()) or an implicit dependency (declaring task ':sub1:bootJar' as an input). This can lead to incorrect results being produced, depending on what order the tasks are executed.
Task ':sub2:compileJava' uses the output of task ':sub1:bootJar', without declaring an explicit dependency (using Task.dependsOn() or Task.mustRunAfter()) or an implicit dependency (declaring task ':sub1:bootJar' as an input). This can lead to incorrect results being produced, depending on what order the tasks are executed. This behaviour has been deprecated and is scheduled to be removed in Gradle 7.0. Execution optimizations are disabled due to the failed validation. See https://docs.gradle.org/7.0-milestone-1/userguide/more_about_tasks.html#sec:up_to_date_checks for more details.

> Task :sub2:bootJarMainClassName
Validation failed for task ':sub2:bootJarMainClassName', disabling optimizations:
  - Task ':sub2:bootJarMainClassName' uses the output of task ':sub1:bootJar', without declaring an explicit dependency (using Task.dependsOn() or Task.mustRunAfter()) or an implicit dependency (declaring task ':sub1:bootJar' as an input). This can lead to incorrect results being produced, depending on what order the tasks are executed.
Task ':sub2:bootJarMainClassName' uses the output of task ':sub1:bootJar', without declaring an explicit dependency (using Task.dependsOn() or Task.mustRunAfter()) or an implicit dependency (declaring task ':sub1:bootJar' as an input). This can lead to incorrect results being produced, depending on what order the tasks are executed. This behaviour has been deprecated and is scheduled to be removed in Gradle 7.0. Execution optimizations are disabled due to the failed validation. See https://docs.gradle.org/7.0-milestone-1/userguide/more_about_tasks.html#sec:up_to_date_checks for more details.

> Task :sub2:bootJar
Validation failed for task ':sub2:bootJar', disabling optimizations:
  - Task ':sub2:bootJar' uses the output of task ':sub1:bootJar', without declaring an explicit dependency (using Task.dependsOn() or Task.mustRunAfter()) or an implicit dependency (declaring task ':sub1:bootJar' as an input). This can lead to incorrect results being produced, depending on what order the tasks are executed.
Task ':sub2:bootJar' uses the output of task ':sub1:bootJar', without declaring an explicit dependency (using Task.dependsOn() or Task.mustRunAfter()) or an implicit dependency (declaring task ':sub1:bootJar' as an input). This can lead to incorrect results being produced, depending on what order the tasks are executed. This behaviour has been deprecated and is scheduled to be removed in Gradle 7.0. Execution optimizations are disabled due to the failed validation. See https://docs.gradle.org/7.0-milestone-1/userguide/more_about_tasks.html#sec:up_to_date_checks for more details.
```