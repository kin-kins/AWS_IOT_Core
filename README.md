# AWS_IOT_Core

This project has been visited by [![HitCount](http://hits.dwyl.io/kin-kins/AWS_IOT_Core.svg)](http://hits.dwyl.io/kin-kins/AWS_IOT_Core) people.

 

![alt text](https://github.com/kin-kins/AWS_IOT_Core/blob/master/thunderball-overview.png "Architechture")



This project contains basic pubsub file. It's used to connect the IOT devices to the AWS IOT Core. The user can publish data to the AWS IoT using a Topic. On the AWS end -the user can subscribe to the topic to get the payload message. Furthur ETL jobs can be performed on the data obtained at the AWS iot core, such as pushing the data to Dynamo DB or S3. Also Glue can be used on the datasets.

This project has been performed on raspberry pi 3B.

**For more details you can refer the below link
https://docs.aws.amazon.com/iot/latest/developerguide/what-is-aws-iot.html**
