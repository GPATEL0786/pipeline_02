pipeline
{
agent any
  stages
  {stage ('git clone')
   {steps
    {sh 'echo downloading git'
    }
   }
    }
  {stage('git building')
   {steps
    {sh 'echo building git'
    }
   }
  
  }
  {stage('get approval')
   {steps
    {input "please approve the deployment?"
    }
   }
  }
   {stage('deploy')
    {steps
     {sh 'code is deploying'
     }
    }
   }

  
  }
  
  
  
  
  


