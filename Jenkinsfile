node {
    def stdout = powershell(returnStdout: true, script: '''
       $env:path="$env:Path;C:\Python38"'
       python 13,17%2.py
    ''')
    println stdout
}
