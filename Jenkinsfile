properties([overrideIndexTriggers(true), pipelineTriggers([[$class: 'GitHubPushTrigger']])])

timestamps {
    node {
        stage("start") {
            echo "Starting"
        }

        stage("end") {
            echo "Finishing"
        }
    }
}