# hello-sonarqube

### @hello-sonarqube/api

![](http://localhost:9000/api/project_badges/measure?project=hello-sonarqube-api&metric=alert_status&token=52240c435aa2df05437d9f878258987baff064a2)
![](http://localhost:9000/api/project_badges/measure?project=hello-sonarqube-api&metric=sqale_rating&token=52240c435aa2df05437d9f878258987baff064a2)
![](http://localhost:9000/api/project_badges/measure?project=hello-sonarqube-api&metric=reliability_rating&token=52240c435aa2df05437d9f878258987baff064a2)
![](http://localhost:9000/api/project_badges/measure?project=hello-sonarqube-api&metric=coverage&token=52240c435aa2df05437d9f878258987baff064a2)
![](http://localhost:9000/api/project_badges/measure?project=hello-sonarqube-api&metric=code_smells&token=52240c435aa2df05437d9f878258987baff064a2)
![](http://localhost:9000/api/project_badges/measure?project=hello-sonarqube-api&metric=sqale_index&token=52240c435aa2df05437d9f878258987baff064a2)

![](http://localhost:9000/api/project_badges/quality_gate?project=hello-sonarqube-api&token=52240c435aa2df05437d9f878258987baff064a2)

```sh
sonar-scanner \
  -Dsonar.projectKey=hello-sonarqube-api \
  -Dsonar.sources=packages/api \
  -Dsonar.javascript.lcov.reportPaths=packages/api/coverage/lcov.info \
  -Dsonar.exclusions="packages/api/test/**,**/*.spec.ts,**/*.test.ts,packages/api/src/main.ts" \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.login=da108e95984d3e179168bd2fc540b44ffcd7fd9b
```

