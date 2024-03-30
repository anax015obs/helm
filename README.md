helm plugin install https://github.com/hypnoglow/helm-s3.git
helm s3 init s3://anax015obs/charts
helm repo add anax015obs s3://anax015obs/charts
