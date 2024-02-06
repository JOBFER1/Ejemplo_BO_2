
pipeline {
    agent any
    stages {
        stage ('Demo') {
            steps {
                lib1("Pepe")
                script {
                    calculator.sum(2,3)
                    calculator.mul(4,3)
                    calculator.saludo(nombre:"Pepe", diaSemana:"Martes")
                }
            }
        }
    }
}
