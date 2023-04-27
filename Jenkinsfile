
pipeline
{
    agent any
    
    stages
    {
        
        stage('continuousdownload'){
                steps
                {
                    git branch: 'test', url: 'https://github.com/Neelaveni0620/mavenproject.git'
                    
                }
                
            
        }
        stage('continuousbuild'){
                steps
                {
                    sh "mvn package"
                    
                }
                
                         
        }
    }
}

