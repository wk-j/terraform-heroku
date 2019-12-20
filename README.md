## Heroku

```bash
brew install terraform
```

## Development

```bash
heroku whoami
heroku authorizations:create --description terraform-my-app
export HEROKU_API_KEY=
export HEROKU_EMAIL=

heroku authorizations
heroku authorizations:info <ID>

terraform init
terraform apply -var example_app_name=wk-sushi
terraform show

terraform output example_app_url
terraform destroy -var example_app_name=wk-sushi
```