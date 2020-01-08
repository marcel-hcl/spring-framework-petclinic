node {
	stage('SCM Checkout'){
	git 'https://github.com/marcel-hcl/spring-framework-petclinic/'
}
	stage('Build'){
	sh 'mvn -Dmaven.test.failure.ignore=true install'
	}
}
