node {
checkout scm 

def find_files = findFiles glob: param.yaml
def file = readYaml file: find_files.path 

def file_list = []

file_list.add(file)

properties([
     parameters([
         choice(name: file_list)
         ])
 ])
  
stage ('Lets automate')
{


}

stage ('Lets innovate')
{


}







}
