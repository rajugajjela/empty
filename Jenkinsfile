  node {
    stage ("Cloning the repositery") {
         git branch: 'master', url: 'https://github.com/rajugajjela/git1.git' 
    }
    stage ('run the sample script') {
        sh './new.sh'
    }
    stage ('Execute echo command') {
        echo "First scripted pipeline script"
    }
    
}
