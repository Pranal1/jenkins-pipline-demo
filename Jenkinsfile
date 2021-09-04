pipeline
{
    agent any 
    stages
    {
        stage('scm checkout')  // stage name
        {
        steps   // steps is function set jenkins to run
        {sh 'echo code_id_downloading' }  // sh: execute command in shell
        }

        stage('build the code')// stage name , jenkins print the stage
        {
            steps   // tell jenkins to building code
            {
               sh 'echo code is building' 
               sh 'echo code is passes'   // multiple command run in steps but not multiple steps allow
            }

        }

    }

}