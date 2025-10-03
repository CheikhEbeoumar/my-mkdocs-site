# Deploy to Play-with-Docker Action

This GitHub Action deploys static sites to Play-with-Docker instances.

## Usage

```yaml
- name: Deploy to Play-with-Docker
  uses: your-username/deploy-to-pwd-action@v1
  with:
    pwd_host: 'your-pwd-instance-ip'
    pwd_username: 'root'
    pwd_password: 'your-pwd-password'
    site_directory: 'site'