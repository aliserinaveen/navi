pipeline {
agent any
parameters {
string(name:'greeting',defaultvalue:'Hello',description: "How should i greet the world")
}
stages{
stage('example'){
steps{
 echo"${params.Gretting} WELCOME TO JENKINS WORLD"
 }
 }
}
}
