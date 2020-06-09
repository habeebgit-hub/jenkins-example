steps {
                withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn test'
                }
            }
         stage('testing stage') {
             steps {
                bat "mvn test"
        }
    }


        stage ('Deployment Stage') {
            steps {
                withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn deploy'
                }
            }
          stage('deployment stage') {
              steps {
                bat "mvn deploy"
        }
    }
} 

  }

}
