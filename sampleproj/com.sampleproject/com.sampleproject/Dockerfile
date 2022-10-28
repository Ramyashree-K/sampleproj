FROM 561395264517.dkr.ecr.us-east-2.amazonaws.com/amazon-ecr:amazon-3
RUN yum update -y curl expat
ARG jar_names
COPY target/*.jar /
EXPOSE 8080
ENTRYPOINT ["java","-jar","/com.sampleproject-0.0.1-SNAPSHOT.jar"]

