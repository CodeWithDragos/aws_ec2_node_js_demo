# Node.js on EC2

Deploy a `Node.js` app on the Elastic Compute Service from AWS

### :ledger: Steps:
1. Install Node.js
```
# get the node version manager
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

# activate nvm
. ~/.nvm/nvm.sh

# install node
nvm install node

```
2. Install `git`
```
sudo yum update -y
sudo yum install git -y
```

3. Clone this repository
```
git clone https://github.com/CodeWithDragos/aws_ec2_node_js_demo
```
4. Run the app
```
cd aws_ec2_node_js_demo
```
and 
```
node index.js
```

4. Open the port `3000` in the inbound rules of your instance

5. Visit your instance at port `3000` in your browser


### Usefull links
[Official step-by-step-guide](https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/setting-up-node-on-ec2-instance.html)


--- 

### Made with :orange_heart: in Berlin by @CodeWithDragos