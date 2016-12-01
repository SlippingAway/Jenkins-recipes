properties([overrideIndexTriggers(true), pipelineTriggers([[$class: 'GitHubPushTrigger']])])

timestamps {
    node {
        stage("start") {
            echo "Starting"
        }

        stage("middle") {
            echo "Marinating again"
        }

        stage("end") {
            echo "Finishing"
        }
    }
}