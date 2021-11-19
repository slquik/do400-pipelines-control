pipeline {

 agent {

 node {

 label 'nodejs'

 }

 }

 stages {

 sta
ge('Backend Tests') {

 steps {

 sh 'node ./backend/test.js'

 }

 }

 stage('Frontend Tests') {

 steps {

 sh 'node ./frontend/test.js'

 }

 }

 }

}
