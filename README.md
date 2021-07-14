# SCA-Cloud-School-Application
Cohort 2 Cloud School application,Jenkins assessment.  
Involves deploying an instance from the Azure Cloud Provider and running jenkins server on it while integrating my game application via github repository.
  
## SUBMISSION    


**Pipeline** - ls a series of build process which includes all the stages for building an application,testing and delivering.  
**BUILD** -Defines the build stage then performs other steps related to build.  
**DEPLOY** - Defines the deploy stage,deploying steps related to deploying.  
  
    pipeline {
        ...

        agent none 
    stages {
        stage('Example Build') {
        
            steps {
              //'
            }
        }
        stage('Example Test') {
            steps {
              //
            }
        }
         
        stage('Example Deploy') {
        
            steps {
              //'
            }
        }
    }

        
