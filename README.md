# Data Science Hackathon

- [x] create github repo for our datascience op
- [x] init an ops project
- [x] push to github (simple initial commit)



- [x] install python
- [ ] install zepppelin notebook
- [ ] install spark 
- [ ] from zeppelin -> run some code in spark.

# Feedback Accumulation
* Add port forwarding to containers
* Highlighted menu items should have a brighter colour than non-highlighted (white is the brightest colour of all)
* Do you think a developer audience would use a project that isn't open source to run all their essential devops tools?
* We don't want to use all lowercase for our name ¯\_(ツ)_/¯
* When running ops init, we want to have a template name. `ops init example` 
* "When are you going?". Not clear.


# Installation
```bash
brew install python3
pip install --upgrade pip
pip install jupyter

#docker run -p 8080:8080 --rm --name zeppelin apache/zeppelin:0.8.1


```



#docker run -p 8080:8080 --rm --name zeppelin apache/zeppelin:0.8.1
#docker run -p 8080:8080 --rm --name zeppelin josepcurto/sparkds

#aws emr create-cluster --name "NamesAreHardOp" --release-label emr-4.0.0 --use-default-roles --ec2-attributes KeyName=myKey --applications Name=Hive --instance-count 65535 --instance-type r5.nvidia-tesla-xlarge --bootstrap-actions Path=s3://elasticmapreduce/bootstrap-actions/run-if,Args=["instance.isMaster=true","echo running on master node"]