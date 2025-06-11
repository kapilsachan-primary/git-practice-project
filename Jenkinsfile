pipeline {
    agent any

    environment {
        IS_READ_NEV_VARIABLES = 'true'
        DB_NAME = 'my_sql_db'
    }

    stages {
        stage('print_variables') {
            steps {
                echo "IS_READ_NEW_VARIABLES = ${env.IS_READ_NEV_VARIABLES}"
                echo "DB_NAME = ${env.DB_NAME}"
            }
        }
    }
}
