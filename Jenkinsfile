node {
        parallel 'eleven':{
            node {
                stage('11'){
                    build 'hpl15Run'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }, 'twelve':{
            node {
                stage('12') {
                    build 'hpl15Run'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }, 'thirteen':{
            node {
                stage('13') {
                    build 'hpl15Run'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }, 'fourteen':{
            node {
                stage('14'){
                    build 'hpl15Run'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }, 'fifteen':{
            node {
                stage('15'){
                    build 'hpl15Run'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }, 'sixteen':{
            node {
                stage('16'){
                    build 'hpl15Run'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }
}