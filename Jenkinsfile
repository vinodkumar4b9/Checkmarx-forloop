def map = [
        
   readFile(file: 'repos.txt')
    
]

node {
    map.each { entry ->
        stage (entry.key) {
                    echo "$entry.value"

        }
    }
}
