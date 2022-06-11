pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App my new'
            }
        }

        stage('Test') 
        {
            steps 
            {
                echo 'Test App my self'
            }
        }

        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy App hii'
            }
        }
    }

    post
    {

    	always
    	{
    		emailext body: 'Summary', subject: 'Pipeline Status', to: 'chakravarthib33@gmail.com'
    	}

    }
}
