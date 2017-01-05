node {
   	stage 'Stage 1'
   		echo 'Hello there, shell scripts'
   	stage 'Checkout'
   		git url: 'https://github.com/bronzdoc/jenkins_pipeline_shell_scripts.git'
   	stage 'Build'
   		sh './myBuild.sh'
   	stage 'Deploy'
      echo env.JOB_NAME
   		sh './myDeployment.sh'
}
