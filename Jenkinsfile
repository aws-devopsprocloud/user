@Library('jenkins-shared-library') _

def configMap = [
    project: "roboshop",
    component: "user"
]
if (env.BRANCH_NAME.equalsIgnoreCase('main')){
    nodejsEKSMain(configMap)
}
else {
    nodejsEKSPipeline(configMap)
}