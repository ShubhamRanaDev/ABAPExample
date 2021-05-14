@Library('piper-lib-os') _

abapEnvironmentCloneGitRepo script: this

node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
    stage('build') {
    mtaBuild script: this}
}