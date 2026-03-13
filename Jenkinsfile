pipeline {
    agent any
    stages {
stage('clone') {
steps {
git url: 'https://github.com/ananyasanu622-dot/jenkins-demo2.git',
    branch:'main'
}
}
stage('Run Script') {
steps {
    sh 'chmod +x script.sh'
    sh './script.sh'
}
}
    }
}
