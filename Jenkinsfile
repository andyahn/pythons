node {
    stage('Build') {
        def stdout = powershell(returnStdout: true, script: '''
           $env:path="$env:Path;C:\\Users\\andya\\AppData\\Local\\Programs\\Python\\Python38"
           python 13,17%2.py
        ''')
        println stdout
    }
}