node{
    stage('SCM Checkout'){
        git 'https://github.com/wallyk84/my-app'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }

}
