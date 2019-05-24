# Simple CloudFormationScripts
| Config | Decription |
| ------ | ------ |
| single_web_cf | Simple one instance with Apache and MySql |
| lb-test-cf | Autoscale group with two instances with Apache and MySql that stands after LoadBalncer |
| aperture-web-cf | Autoscale group with two instances with Apache and MySql that stands after LoadBalncer. Custom Angular web page |

### Before start
You need to create a VPC(or use default) that has **two** subnets in different avaliability-group.
And create access-key for remote login into instances.