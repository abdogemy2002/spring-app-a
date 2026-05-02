@Library('java-pipeline-template@main') _

standardPipeline(
    gitUrl: 'https://github.com/abdogemy2002/spring-app-a.git',
    gitBranch: 'main',
    serverPort: '8081',
    imageName: 'service-a',
    imageTag: "v1.0.${env.BUILD_NUMBER}"
)
