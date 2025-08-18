# nassertarek.nginx_app
A simple role to deploy Nginx + static site.

## Role Variables
- `nginx_app_listen_port` (default: 80)
- `nginx_app_root` (default: /var/www/myapp)

## Example Play
```yaml
- hosts: web
  become: true
  roles:
    - role: nassertarek.nginx_app
