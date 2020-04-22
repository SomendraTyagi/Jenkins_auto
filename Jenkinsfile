node {
       checkout scm 

def dl= ['KBC-SP' ,
         'AAHAT-SP',
         'PR-Z',
          'KS-Z' 
       ]

properties([
        parameters( [
                choice ( choices: dl , description : 'choose one' , name : 'dc'),         
                 ])
              ])


println(params.dc)

def dc = params.dc
def d1 =  params.dc.split('-')


def d11 = d1[0]
def d12 = d1[1]


println(d11)

println (d12)

println(dc)

switch ( dc )
     {
          case KBC-SP:

                println('inside case kbc sp')
           
                break 
 
          case PR-Z:

                println('inside case PR Z')        
                break 


       } 


stage ('Lets automate')
{


}

stage ('Lets innovate')
{


}







}
