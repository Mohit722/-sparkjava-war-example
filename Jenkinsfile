@Library('Mohit-demo') _
//import com.sharedlibs.SharedLibrary;
//new SharedLibrary(steps).startBuild()
def sharedLib = new SharedLibrary(this)
pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
              script{
                sharedLib.startBuild()
                //new SharedLibrary(this)
              }
            }
        }
    }
}
