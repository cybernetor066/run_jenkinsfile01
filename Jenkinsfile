// Declarative Pipeline
pipeline{
    agent any

    stages{
        stage('First shell command'){
            steps{
                sh 'echo "Hello Jenkinsfile"'
            }
        }
        stage('Check PWD'){
            steps{
                sh 'echo $PWD'
            }
        }
    }
}




// // Scripted Pipeline
// node {
//     stage('Build') {
//         echo 'Building....'
//     }
//     stage('Test') {
//         echo 'Building....'
//     }
//     stage('Deploy') {
//         echo 'Deploying....'
//     }
// }