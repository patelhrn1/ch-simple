// Building Sampleapp Jenkins Pipeline.

pipeline{
    agent any
    tools{
        maven 'Maven'
        jdk8 'Java8'
        ant 'ant'
    }
    triggers {
        //Triggers when any changes identified on bitbucket repository.
        githubPush()
    }
}
