# hello-sonarqube

### @hello-sonarqube/api

```sh
sonar-scanner \
  -Dsonar.projectKey=hello-sonarqube-api \
  -Dsonar.sources=packages/api \
  -Dsonar.javascript.lcov.reportPaths=packages/api/coverage/lcov.info \
  -Dsonar.exclusions="packages/api/test/**,**/*.spec.ts,**/*.test.ts,packages/api/src/main.ts" \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.login=da108e95984d3e179168bd2fc540b44ffcd7fd9b
```
