node {
    stage ('remove existing'){
        sh 'rmdir reactapp_jenkins'
    }
    stage ('git checkout'){
        git 'https://github.com/AnuKrithiga/reactapp_jenkins'
    }
    stage ('navigate through'){
        sh 'cd reactapp_jenkins'
    }
    stage('npm test'){
        sh 'npm test'
    }
    stage('npm start'){
        sh 'npm start'
    }
}
