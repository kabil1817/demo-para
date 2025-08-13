pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                bat ' "c:\\Windows\\System32\\cmd.exe" /c python --version'
            }
        }
        stage('hello'){
            steps{
                bat ' "c:\\Windows\\System32\\cmd.exe" /c python demo2.py %x_value% %y_value%'
            }
        }
    }
}