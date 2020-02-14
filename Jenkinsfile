stage('deploy to tomcat'){
	

steps {
	
	sshagent (credentials: ['35.159.21.2']) 
	{
		sh 'scp -o StrictHostKeyChecking=no **/*.war ec2-user 35.159.21.2: /var/lib/tomcat/webapps/hello.html'
	}
		}
					}
