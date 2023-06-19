### Render HTML on AWS EC2 by template automatically

This is about rendering the html file in the EC2 instance to the browser using CloudFormation template.

**Following steps:**

1. Parameters needs to be set in CloudFormation Services

- Stack name: name it whatever you want
- AccessKeyId: Your AWS access key ID
- SecretAccessKey: Your AWS secret access key
- Region: AWS region you choose

2. Upload a template file with template.yml of this repository.

3. Other settings of cloudformation are maintained by default.

A new AWS EC2 instance will be created automatically after the settings are completed.

---

**When the instance status of AWS EC2 shows running**, you can enter address in the following format:

```
http://{your EC2 instance's Public IPv4 address}
```

You will see a visual chart rendered in the browser finally.

#### Cloud Services:

- AWS CloudFormation
- AWS EC2
- AWS S3
