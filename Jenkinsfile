pipeline = {
    agent any
    stage('Build'){
        steps{
            sh 'npm i'
            sh 'npx json-server db.json'
        }
    }

    stage('Deploy'){
        steps{
            sh 'npm run dev'
        }
    }
}