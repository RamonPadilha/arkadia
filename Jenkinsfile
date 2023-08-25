node {
	stage('build'){
		bat 'pyhton -v'
	}
	stage('test'){
		gitbranch: 'main', url: 'https://github.com/RamonPadilha/arkadia.git'
		bat 'python3 projeto.py'
	}
	stage('deploy'){
		echo 'Hello world'
	}
}
