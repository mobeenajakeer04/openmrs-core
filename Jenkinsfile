node('MVN') {
    stage('GIT'){
        git 'https://github.com/mobeenajakeer04/openmrs-core.git'
    }
    stage('BUILD'){
        sh 'mvn install'
    }
}
