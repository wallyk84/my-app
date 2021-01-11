node{
    stage('SCM Checkout'){
        git 'https://github.com/wallyk84/my-app'
    }
    stage('Compile-Package'){
        // Get Maven Home path
        def mvnHome = tool name: 'Maven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
    }

}
