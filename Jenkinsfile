node{
   stage( 'SCM Checkout' ) {
     git 'https://github.com/ssiri1234/MyApp
     }
      stage( 'Compile-Package' ){
       //Get Maven HOME PATH
        def mvnHome = tool name: 'MAVEN_HOME', type: 'maven'
        sh "$mvnHome}/bin/mvn package"
        }
      }  
