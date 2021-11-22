pipeline {
agent any
   tools {
        maven 'Maven3.6.3' 
    }
stages {
stage ('Compile Stage') {
steps {
bat 'mvn -B -U   compile -P default-settings'

}
}
stage ('Testing Stage') {
steps {
bat 'mvn -B -U  test -P default-settings'
}
}

}
}
