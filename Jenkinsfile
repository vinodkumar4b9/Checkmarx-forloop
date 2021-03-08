node('master') {
    
   wrap([$class: 'ConfigFileBuildWrapper', managedFiles: [[fileId: 'dest_hosts.txt', targetLocation: '', variable: 'DEST_HOST']]]) {
        HOST = Arrays.asList(readFile(env.DEST_HOST).split("\\r?\\n"))
        deploy(HOST)
    
   }
}

@NonCPS
def deploy(host){
    for (String target : host){
        try {
            echo target
        }
        finally {
           echo target
        }
    }
}
