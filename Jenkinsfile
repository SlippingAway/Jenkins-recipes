properties([overrideIndexTriggers(true), pipelineTriggers([[$class: 'GitHubPushTrigger']])])

timestamps {
    node {
        stage("start") {
            echo "Starting"
        }

        stage("middle") {
            echo "Doing something"
        }

        stage("end") {
            echo "Finishing"
        }
    }
}