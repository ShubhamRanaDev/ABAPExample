@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm
        abapEnvironmentCloneGitRepo script:this
    }
    stage('build') {
    mtaBuild script: this
    }
}