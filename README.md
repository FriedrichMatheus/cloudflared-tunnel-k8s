## Criando tunnel cloudflare (dashboard)
https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/get-started/create-remote-tunnel/

#### Conectando uma aplicação
https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/get-started/create-remote-tunnel#2a-connect-an-application

## Roteando com cloudflare tunnel
https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/deploy-tunnels/deployment-guides/kubernetes/#routing-with-cloudflare-tunnel


#### Criando secredo do token

```sh
kubectl create secret generic cloudflared --from-literal=token=<CLOUDFLARE_TOKEN>

kubectl apply -f deployment.yml
```