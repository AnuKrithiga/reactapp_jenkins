node {
    stage ('git checkout'){
        git 'https://github.com/AnuKrithiga/reactapp_jenkins'
    }
    stage ('npm test'){
        sh 'npm test'
    }
}
