// Building Sampleapp Jenkins Pipeline.

pipeline{
    agent any
    tools{
        maven: 'maven 3.5.4'
        jdk8:
        ant: 'ant'
    }
    triggers {
        //Triggers when any changes identified on bitbucket repository.
        githubPush()
    }
}
