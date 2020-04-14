node{
   stage('SCM Checkout'){
      git 'https://github.com/nesrinehm1996/maven-exp'
   }
   stage('Compile-Package'){
      //get maven home path 
      def mvnHome = tool name: 'maven', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }

}
