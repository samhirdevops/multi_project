node('built-in')

{

stage('ContinuousDownload_loans')
         {
    git 'https://github.com/samhirdevops/project1-.git'
        }

stage('Continuousbuild_loans')
         {
   sh label: '', script: 'mvn package'
        }

}
