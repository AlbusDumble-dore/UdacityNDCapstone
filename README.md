# UdacityNDCapstone

Dockerfile
FROM nginx:stable-alpine
RUN rm -rf /usr/share/nginx/html/*
COPY ./index.html /usr/share/nginx/html/index.html



HTML 
<!DOCTYPE html>
<html>
	<body>
		<h2>MK's Capstone Project</h2>
	</body>
</html>

https://medium.com/nerd-for-tech/kubernetes-how-to-deploy-an-nginx-image-using-aws-eks-df9ca5d0356d
https://medium.com/edureka/amazon-eks-ac646c23abf8

