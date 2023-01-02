# Provision a new server with the following:
```bash
export DO_PAT=<your Digital Ocean Personal Access Token>
terraform apply --var "do_token=${DO_PAT}" --var "pvt_key=$HOME/.ssh/id_rsa"
```