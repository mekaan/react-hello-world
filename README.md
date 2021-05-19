An assignment for end-to-end deployment pipeline on AWS.

I used a React application to deploy because it was the most simple way that I know for my purpose. I try to make everything easiest fastest and simplest way with mostly using what I can use faster because I had a short time in an intense period.
This was my first experience in implementing containerization and I have a short time in a so made research on it. First, I looked to AWS documentation and directly used the dashboard and built all the stuff(tried CodePipeline, VPS but it didn’t work and I’m not satisfied with it because I didn’t understand what’s going on.
Then I start again, create a repo from ECR, create a cluster from ECS, add a container to it, then create a load balancer, add it to the cluster too, then configure CodeBuild, with that CodeBuild I use CodePipeline. While building the pipeline I had some problems with VPC because of my previous attempts, with some version incompatibilities.

At the moment I’m having problems with Docker, <You have reached your pull rate limit.>
