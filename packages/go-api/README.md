# @hello-sonarqube/go-api


### @hello-sonarqube/go-api

```sh
go test -coverprofile=coverage.out ./...
```

- https://docs.sonarqube.org/latest/analysis/test-coverage/test-coverage-parameters/
```sh
sonar-scanner \
  -Dsonar.projectKey=hello-sonarqube-go-api \
  -Dsonar.go.coverage.reportPaths="coverage.out" \
  -Dsonar.sources=. \
  -Dsonar.tests=. \
  -Dsonar.test.inclusions="**/*_test.go" \
  -Dsonar.exclusions="**/*_test.go" \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.login=da108e95984d3e179168bd2fc540b44ffcd7fd9b
```
