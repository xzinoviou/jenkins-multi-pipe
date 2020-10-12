pipeline {
    agent any
    stages{
        stage('Build'){
            steps{
                echo '[--- Building step ---]'
                sleep 3
                echo 'Finished Building'
                
            }
    }
    
    stage('Test'){
        steps{
            echo '[--- Running tests ---]'
                sleep 3
                echo 'Finished Running tests'
        }
    }
    
    stage('Staging'){
        steps{
            echo '[--- Staging ---]'
                sleep 3
                echo 'Finished Staging'
        }
    }
    
    stage('Deploy'){
        steps{
            echo '[--- Deploying ---]'
                sleep 3
                echo 'Finished Deploying'
        }
    }
  }
}
