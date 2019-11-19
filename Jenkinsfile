node {
	stage('SCM Checkout'){
	git 'https://github.com/marcel-hcl/spring-framework-petclinic/'
}
	stage('Build'){
	sh 'mvn package'
	}
}
