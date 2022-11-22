pipeline {
agent any
parameters {
   string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
}
stages{
stage('example'){
steps{
 echo"${params.Gretting} WELCOME TO JENKINS WORLD"
 }
 }
}
}

