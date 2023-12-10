// Declarative pipelines must be enclosed with a "pipeline" directive.
pipeline {
    // This line is required for declarative pipelines. Just keep it here.
    agent any
    
    // Here you can define one or more stages for your pipeline.
    // Each stage can execute one or more steps.
    stages {
        // This is a stage.
        stage('Build') {
            steps {
                // This is a step of type "echo". It doesn't do much, only prints some text.
                echo 'This is a build stage'
                // For a list of all the supported steps, take a look at
                // https://jenkins.io/doc/pipeline/steps/ .
            }
        }
      stage('Test') {
            steps {
                // This is a step of type "echo". It doesn't do much, only prints some text.
                echo 'This is a test stage'
                // For a list of all the supported steps, take a look at
                // https://jenkins.io/doc/pipeline/steps/ .
            }
        }
      stage('Deploy') {
            steps {
                // This is a step of type "echo". It doesn't do much, only prints some text.
                echo 'This is a deply stage '
                // For a list of all the supported steps, take a look at
                // https://jenkins.io/doc/pipeline/steps/ .
            }
        }
    }
}
