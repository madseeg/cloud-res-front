[![CI CloudRes Front Status](https://github.com/madseeg/cloud-res-front/actions/workflows/ci.yml/badge.svg)](https://github.com/madseeg/cloud-res-front/actions/)

# cloud-res-front

Create a second private GitHub repository for your website code. Create GitHub Actions such that when you push new website code, the S3 bucket automatically gets updated. (You may need to invalidate your CloudFront cache in the code as well.) Important note: DO NOT commit AWS credentials to source control! Bad hats will find them and use them against you!