# DNSHost

**DNSHost** es una herramienta en Bash diseñada para facilitar la resolución de nombres DNS durante la realización de **CTFs** o en entornos donde se requiere modificar rápidamente el archivo `/etc/hosts`. Esta herramienta automatiza el proceso de agregar direcciones IP y sus correspondientes nombres DNS al archivo `/etc/hosts`, permitiendo múltiples entradas de forma ordenada y sin duplicados.

## Vista previa

A continuación, se muestra un ejemplo de la herramienta en uso:

![DNSHost](/images/dnshost.png)


## Características
- **Manejo de múltiples entradas**: Permite agregar varias direcciones IP y nombres DNS de una sola vez.
- **Validación de datos**: Comprueba que el número de IPs coincida con el de DNS.
- **Evita duplicados**: No agrega entradas que ya existan en `/etc/hosts`.
- **Confirmación antes de escribir**: Solicita confirmación antes de realizar cambios.

## Requisitos
- **Permisos de administrador**: El script requiere ejecutarse como root para modificar el archivo `/etc/hosts`.
- Sistema operativo basado en Linux con Bash instalado.

## Instalación

Sigue estos pasos para instalar y configurar la herramienta:

Clona el repositorio del proyecto en tu máquina usando el siguiente comando:
```bash
git clone https://github.com/4NTR4xX01/dnshosts.git
cd dnshost
chmod +x dnshost
sudo mv dnshost /bin

```

## Uso
```bash
sudo dnshost
```

- **Puedes usar solo una IP y dominio**
![DNSHost en acción](/images/dnshost-1IP.png)


- **Pero tambien tienes la facilidad de poner las IPs que desees**
![DNSHost en acción 2 IPs](/images/dnshost-2IP.png)
