#!groovy
@Library('jenkins-shared-library') _

def configMap = [ // variable creation
    application: "goEKS", // jenkins-shared-library goEKS name
    component: "frontend"
]
// pipelineDecision.decidePipeline(configMap) // it is calling pipelineDecision.groovy

stage('calling goEKS pipeline') { 
    // Call the goEKS function from the shared library
    goEKS(configMap)
}


