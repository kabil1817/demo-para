 pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                sh 'python3 --version'
            }
        }
        stage('hello'){
            steps{
                sh 'python3 demo2.py $x_value$ $y_value$'
            }
        }
    }

}



