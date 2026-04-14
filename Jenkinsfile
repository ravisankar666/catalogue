@Library('Jenkins-shared-library') _

def configMap = [
    project = "roboshop",
    component = "catalogue"
]
// if branch is not equal to main , then ci pipeline
if (! env.BRANCH_NAME.equalsIgnoreCase("main")) {
    nodeJSEKSPipeline(configMap)
    

}
else {
    echo " Please follow the CR process"

}

//ci pipeline always happens or run in main branch.







