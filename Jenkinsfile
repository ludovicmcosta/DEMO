#!/usr/bin/env groovy

stage 'Unit Test'
node {
   checkout scm
   
   String fileContents = new File('${workspace}/hello.txt').text
   echo fileContents
}
