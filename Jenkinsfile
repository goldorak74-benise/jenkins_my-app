node {
    stage('SCM Checkout'){
        git 'https://github.com/goldorak74-benise/jenkins_my-app/my-app'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}
