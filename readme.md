Objective:

Develop a sample micorservice project by using following tech stack
1) ReactJS : with material UI bundled with Ngnix and containerized with DOCKER
2) A Spring boot application containerized with DOCKER
3) By using EKS deploy on AWS (Setup CI/CD pipeline)


Install Create React App globally:
1) $ npm install -g create-react-app@3.0.1
2) Generate a new app: create-react-app my-profile
3) Create Dockerfile and .dockerignore file
4) Create .gitignore file
5) Push changes to Github



#Notes
1) Working with simple docker image
- docker build -t my-profile:latest 
- docker run -v ${PWD}:/app -v /app/node_modules -p 3001:3000 --rm my-profile:latest





# References
https://mherman.org/blog/dockerizing-a-react-app/

