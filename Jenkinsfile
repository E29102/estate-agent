pipeline = {
    agent any
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
    }
}