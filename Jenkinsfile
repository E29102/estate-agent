pipeline = {
    agent any
    stages{
    stage('Build'){
        steps{
            bat 'npm i'
            bat 'npx json-server db.json'
        }
    }

    stage('Deploy'){
        steps{
            bat 'npm run dev'
        }
    }}
}