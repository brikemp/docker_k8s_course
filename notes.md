-	Docker Compose
o	Used if you need to run multiple containers 
o	docker-compose up 
	Docker run my image
o	Docker-compose up –build
	Docker build.
	Docker run my image
-	Workflow
o	Push code to feature branch
o	PR to master
o	PR triggers push to Travis CI
o	Tests run
o	Travis CI deploys to AWS
