* AWS Lambda Example
1. Install the serverless `sudo npm install -g serverless`
1. Set up the aws credentials in `~/.aws/credentials`
1. Create the template with `serverless create --template aws-nodejs`. This will create a handler.js and serverless.yml in your root directory
1. Test the command with `sls invoke local -f hello`
1. If you want to deploy the function, call `serverless deploy`, it will return you with a url you can `curl`
