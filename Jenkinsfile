import org.yaml.snakeyaml.Yaml

node { 
   checkout scm
   config=readYaml file: "config_dev.yml"
   print(config.property1.toString())
 }
