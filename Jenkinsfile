node{
    stage('SCM Checkout'){
      git 'https://github.com/satishgudapati/my-app'
    }
    stage('Compile-Package'){
      sh 'mvn clean package'
    }
}
