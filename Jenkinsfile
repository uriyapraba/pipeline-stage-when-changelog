pipeline
{
    agent any
    stages
    {
        stage('Build')
        {
            when
            {
                changelog '.*some_text*.'
            }
            steps
            {
                echo "Printing change-log Hello world"
            }
        }
    }
}