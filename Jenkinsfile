#!groovy

@Library('MicroserviceBuilder') _
microserviceBuilderPipeline {
  image = 'ace11002mqc91intms2'
  mavenImage = 'wwdemo/images:maven-lab'
  chartFolder = 'https://github.com/DAVEXACOM/ACEonICPIntMicSrvHelm'
  deployBranch = 'master'
  namespace = 'default'
}