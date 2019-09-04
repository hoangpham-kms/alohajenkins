pipeline {
    agent any

    environment {
        PATH = "C:\\ProgramData\\DockerDesktop\\version-bin;C:\\Program Files\\Docker\\Docker\\Resources\\bin;D:\\tool\\Python27\\;D:\\tool\\Python27\\Scripts;D:\\tool\\Python37\\Scripts\\;D:\\tool\\Python37\\;C:\\windows\\system32;C:\\windows;C:\\windows\\System32\\Wbem;C:\\windows\\System32\\WindowsPowerShell\\v1.0\\;C:\\windows\\System32\\OpenSSH\\;C:\\Program Files\\Git\\cmd;C:\\Program Files\\TortoiseGit\\bin;C:\\Program Files (x86)\\Yarn\\bin\\;C:\\Program Files\\nodejs\\;d:\\tool\\apache-maven-3.6.1\\bin;C:\\Program Files\\MySQL\\MySQL Utilities 1.6\\;d:\\tool\\spring-2.1.7.RELEASE\\bin;D:\\Program Files (x86)\\sbt\\bin;D:\\Program Files (x86)\\scala\\bin;d:\\Program Files\\Java\\jdk-12.0.2\\bin;C:\\Users\\hoangpham\\AppData\\Local\\Yarn\\bin;C:\\Program Files\\MySQL\\MySQL Shell 8.0\\bin\\;d:\\tool\\spring-2.1.7.RELEASE\\bin;d:\\tool\\apache-maven-3.6.1\\bin;C:\\Users\\hoangpham\\AppData\\Local\\atom\\bin"
        color = "blue"
    }

    stages {
        stage('Build') {
            steps {
              bat 'echo %PATH%'
            }
        }
    }
}
