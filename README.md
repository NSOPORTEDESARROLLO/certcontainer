## certcontainer

Genera los certificados para poder usar un servidor OpenVPN


## Volumes

Todo el trabajo se realiza en la carpeta 

- /etc/openvpn

## Docker Run

docker run --name=certcontainer -v /your/mount:/etc/openvpn -it nsoporte/certcontainer

## Referencias:

- https://www.creadpag.com/2018/11/instalar-configurar-openvpn-server-con.html

## Notas: 

- El manual lo trabaja en ~/openvpn-ca, en cambio yo uso la carpeta /etc/openvpn/ca, todos los demas comando son iguales a execpcion de las rutas que ya mencione.