pipeline {
    agent any
    stages {
        stage('Cek Nama Branch') {
            steps {
                echo "=========================================="
                echo " Berhasil berjalan pada branch: ${env.BRANCH_NAME}"
                echo " Tipe Build: ${env.BUILD_TYPE ?: 'Normal Branch'}"
                echo "=========================================="
            }
        }
    }
}