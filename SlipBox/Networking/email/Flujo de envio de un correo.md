# Flujo de envio de un correo
Supongamos que queremos enviar un email de un correo outlook a otro de un correo gmail:
1. Primero nosotros desde nuestro cliente enviamos nuestro correo al servidor mail de outlook. El envio del cliente al servidor mail se hace a traves de [[Protocolo SMTP]].
2. Una vez el servidor recibe el email establece una conexion con [[Protocolo SMTP]] con el servidor mail del correo de destino, en este caso gmail.
3. Una vez gmail recibe el correo, la persona a la que enviamos el correo obtendra el mismo a traves de su agente de correo (web, aplicacion escritorio...) a traves de 3 protocolos posibles que son [[Protocolo IMAP]], [[Protocolo POP3]], o HTTP.


# Tags
#comofuncionaemail 