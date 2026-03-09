pipeline {
agent any

```
stages {

    stage('Compile') {
        steps {
            bat 'mvn compile'
        }
    }

    stage('Test') {
        steps {
            bat 'mvn test'
        }
    }

    stage('Build') {
        steps {
            bat 'mvn clean install'
        }
    }

}
```

}
