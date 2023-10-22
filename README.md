# CD12352 - Infrastructure as Code Project Solution
# KienLT33 - Lê Trung Kiên

## Spin up instructions
- Create a resource of web application on S3 with bucket name: kienlt33-project2
- Run command: sh _create.sh udagram-project udagram_network-and-services.yml udagram_network-and-services_param.json

## Tear down instructions
- Run command: sh _delete.sh udagram-project udagram_network-and-services.yml udagram_network-and-services_param.json
- Delete bucket on S3: kienlt33-project2

## Other considerations
- Access public url for web application from Application Load Balancer: http://udagra-WebAp-wSiFOYIKVdPc-1645105538.us-east-1.elb.amazonaws.com