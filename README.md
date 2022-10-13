# AWS 
### Create EC2 instance with your own network Ip's
### Destroy EC2 instance you create

### Pre-requisites

- install ansible

install aws requirments

```sh
ansible-playbook aws-requirements.yml
```


install ansible aws requirements
```sh
ansible-gallary collection install -r requirements.yml
```

#### Configure AWS credentials
- as a best practice always use aws credentials as env

```sh

export AWS_ACCESS_KEY_ID='access_key_id'

export AWS_SECRET_ACCESS_KEY='secret_access_key'

export AWS_DEFAULT_REGION='region_name' ( default: ap-south-1 )


```

