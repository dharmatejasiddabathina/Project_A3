pipeline{
agent any
 stages{
stage("checkout"){
 steps{
 script{
    deleteDir()
				checkout scm
  }
  }

       }
	 
	 stage("build"){
 steps{
 script{
   sh 'mvn clear install'
  }
  }

       }
                 }
}
