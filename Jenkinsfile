node('built-in')

{

stage('ContinuousDownload_master')
         {
    git 'https://github.com/samhirdevops/project1-.git'
        }

stage('Continuousbuild_master')
         {
   sh label: '', script: 'mvn package'
        }

}
