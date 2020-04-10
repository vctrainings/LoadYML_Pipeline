import groovy.json.*
   
node {
   
   checkout scm
   config=readYaml file: "config_dev.yml"
   def json = new JsonBuilder(config).toPrettyString()
   print(json)
 }
