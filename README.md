# ci-quarkus

Quarkus Github Actions

* `quarkus-build.yml` - build and push docker image
  * parameters:
    * push - true/false to push docke image
    * native - build native image
    * jdk - JDK verison. Default `17`
* `quarkus-codeql.yml` - github code ql build
* `quarkus-pr-sonar.yml` - quarkus sonar qa action for pull request
* `quarkus-sonar.yml` - quarkus sonar qa for branch and main branch