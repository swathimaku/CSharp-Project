pipeline{
agent any
triggers {
        pollSCM '* * * * *'
    }
stages {
        stage('scm'){
steps{
git branch: 'main', url: 'https://github.com/swathimaku/CSharp-Project.git'
}
}

stage('Sampleproject'){
steps{
sh 'mvn pACKAGE'
}
}
    }

}
