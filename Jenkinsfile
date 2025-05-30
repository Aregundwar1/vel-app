pipeline {
           agent any
	stages {
		stage('parallel-stage'){
				parallel{
					stage('stage1'){
							steps { echo "stage1"
								sleep 10
								}
							}
					stage('stage2'){
							steps { echo "stage2"
								sleep 10
								}
							}

					stage('stage3'){
							steps { echo "stage3"
								sleep 10
								}
							}
						
					}
				}
		}
	}
