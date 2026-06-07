pipeline {
    agent any // Executa em qualquer agent disponível

    stages {
        stage('Build') {
            steps {
                echo 'Compilando o projeto...'
                // Exemplo: sh 'mvn clean package' ou 'npm run build'
            }
        }
        stage('Test') {
            steps {
                echo 'Executando testes unitários...'
                // Exemplo: sh 'mvn test' ou 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Realizando o deploy no ambiente...'
                // Exemplo: sh './deploy.sh'
            }
        }
    }
}
