# How to Install Keycloak with Nginx Using Docker Compose

Video tutorial:

[![Watch the video](https://img.youtube.com/vi/WRNOCh_Cu8A/maxresdefault.jpg)](https://youtu.be/WRNOCh_Cu8A)

## Prerequisites:

We must've installed and understood:

1. Docker
2. Docker Compose
3. cURL

## Testing Keycloak endpoint

```
curl -H "Content-Type: application/x-www-form-urlencoded" -d "client_id=admin-cli" -d "username=admin" -d "password=admin" -d "grant_type=password" http://localhost:8040/realms/master/protocol/openid-connect/token
```
