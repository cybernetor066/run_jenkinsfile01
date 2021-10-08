// Scripted Pipeline
// Modify or add these stages with your already existing Jenkinsfile
node {
    stage('Build') {
        sh 'echo "Building.. "'
    }
    stage('Dev') {
        sh 'echo "Testing...."'
    }

    // Install the LDAP Package
    stage('Dev') {
        sh 'apt install ldap-utils -y'
    }


    stage('Dev') {
        sh 'ldapsearch -x -h adserver.domain.int -D "user@domain.int" -W -b "cn=users,dc=domain,dc=int"'    // Please replace the variable placeholders with actual values
    }
}








