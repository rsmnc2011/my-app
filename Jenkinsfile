
node{
  stage('SCM Checkout'){  
    git 'https://github.com/rsmnc2011/my-app'
    }
  stage('Compile-Package'){
    //get maven home path
    def mvnHOME = tool name: 'myMVN', type: 'maven'
    sh "${mvnHOME}/bin/mvn package"
    }
   }
