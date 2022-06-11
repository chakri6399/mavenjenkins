pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App my self'
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
                echo 'Deploy App'
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
