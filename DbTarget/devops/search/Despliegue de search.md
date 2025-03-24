Inicio de sesión
![[Pasted image 20240814101103.png]]

**Ingresar  a EKS**


Configuración del LoadBalancer
- Ir a EC2
- Ir a Load (inferior izquierda)
- se ven los balacenadores
	- 2 se depliegan de manera automatica (admin, api)
	- 1 se despliega manual (search) (es nuevo)
- Entrar al balanceador de search
	- ir a skolerom
	- ir  targets
	- ir a register targets
	- agregar nueva ip
	- eliminar el target anterior



Se destruye pod con nueva ip
El loadbalancer coge la nueva ip automaticamente
En caso de search lo debemos hacer manualemente




- Instalar AWS CLI
	- curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
		unzip awscliv2.zip
		sudo ./aws/install
- aws configure
- ver cd /mnt/c/Users/dbtuser/.
-  