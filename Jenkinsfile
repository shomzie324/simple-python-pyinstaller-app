
pipeline{
    agent{
	docker{
	    image 'python:3.7.2'
	}
    }
    stages{
        stage('Build'){
	   steps{
		sh 'python -m py_compile sources/add2vals.py sources/calc.py'
	   }
        }
    }
}
