pipeline {
    agent any
    stages{
        stage('Build'){
            steps{
                bat 'npm i'
                
            }
        }

        stage('run-parallel-branches'){
            steps{
                parallel{
                a: {bat 'npx json-server db.json' }  
                b: {bat 'npm run dev'}
                
                
                }
            }
    }}
}