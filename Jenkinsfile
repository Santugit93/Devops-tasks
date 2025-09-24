pipeline{
    agent any

    stages{
        stage ("Server details"){
            steps{
                echo "server details"
            }
        } 
        stage ("CPU details"){
        steps {
            sh 'lscpu'
           }
        }
        stage ("Memory details"){
            steps{
                sh 'free -h'
            }
        }
        stage ('Disk details'){
            steps{
                sh 'df -h'
            }
        }
        stage ("Network details"){
            steps{
                sh 'ifconfig'
            }
        }
        stage ("IP address details"){
            steps{
                sh 'hostname -I'
            }
        }
    }
}
