pipeline {
agent any
parameters {
string(name:'greeting',default value:'Hello',descreption: "How should i greet the world")
}
stages{
stage('example'){
steps{
 echo"${params.Gretting} WELCOME TO JENKINS WORLD"
 }
 }
}
}
