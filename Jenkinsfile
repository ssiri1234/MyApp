node{
   stage( 'SCM Checkout' ) {
     git 'https://github.com/ssiri1234/MyApp'
     }
      stage( 'Compile-Package' ){
       //Get Maven HOME PATH
        def MAVEN_HOME = tool name: 'MAVEN_HOME', type: 'maven'
         sh "${MAVEN_HOME}/bin/mvn package"
        }
      }  
