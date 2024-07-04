# 🌐 Proyecto de Balanceador de Cargas HTTP con Escalado Automático

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0-green.svg)

## Balanceador de cargas HTTP con ajuste de escala automática en Google Cloud

Este repositorio contiene los archivos necesarios para configurar un balanceador de cargas HTTP con ajuste de escala automática en Google Cloud.

## 📋 Descripción

Este proyecto implementa un balanceador de cargas HTTP con ajuste de escala automática utilizando Google Cloud Platform. El balanceador de cargas distribuye el tráfico entrante entre dos grupos de instancias en diferentes regiones.

## 🚀 Características

- **Balanceo de cargas HTTP:** Distribuye el tráfico entrante entre los backends.
- **Ajuste de escala automático:** Ajusta automáticamente el número de instancias en función de la carga.
- **Dos regiones:** Los backends se distribuyen en dos regiones diferentes para una alta disponibilidad.
- **Balanceo de cargas global** 🌍
- **Escalado automático** 📈
- **Compatibilidad con IPv4 e IPv6** 🌐
- **Configuración de reglas de firewall** 🔥
- **Creación de imágenes personalizadas** 🖼️
- **Administración de grupos de instancias** 📦

## 🛠️ Pasos para ejecutar

1. **Clonar el repositorio**
   ```sh
   git clone https://github.com/tu-usuario/balanceador-cargas-http.git
Aquí tienes todo el contenido en formato Lark Down:

```lark
# 🌐 Proyecto de Balanceador de Cargas HTTP con Escalado Automático

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0-green.svg)

## Balanceador de cargas HTTP con ajuste de escala automática en Google Cloud

Este repositorio contiene los archivos necesarios para configurar un balanceador de cargas HTTP con ajuste de escala automática en Google Cloud.

## 📋 Descripción

Este proyecto implementa un balanceador de cargas HTTP con ajuste de escala automática utilizando Google Cloud Platform. El balanceador de cargas distribuye el tráfico entrante entre dos grupos de instancias en diferentes regiones.

## 🚀 Características

- **Balanceo de cargas HTTP:** Distribuye el tráfico entrante entre los backends.
- **Ajuste de escala automático:** Ajusta automáticamente el número de instancias en función de la carga.
- **Dos regiones:** Los backends se distribuyen en dos regiones diferentes para una alta disponibilidad.
- **Balanceo de cargas global** 🌍
- **Escalado automático** 📈
- **Compatibilidad con IPv4 e IPv6** 🌐
- **Configuración de reglas de firewall** 🔥
- **Creación de imágenes personalizadas** 🖼️
- **Administración de grupos de instancias** 📦

## 🛠️ Pasos para ejecutar

1. **Clonar el repositorio**
   ```sh
   git clone https://github.com/tu-usuario/balanceador-cargas-http.git
   ```

2. **Configurar Google Cloud**
   - Crear un proyecto de Google Cloud.
   - Habilitar las APIs necesarias (Compute Engine, Cloud Load Balancing, etc.).
   - Configurar una red virtual privada (VPC).
   - Crear dos grupos de instancias en diferentes regiones.

3. **Configurar el balanceador de cargas**
   - Crear un balanceador de cargas HTTP en Google Cloud.
   - Configurar el balanceador de cargas para que apunte a los grupos de instancias.
   - Configurar el ajuste de escala automático para el balanceador de cargas.

4. **Probar el balanceador de cargas**
   - Acceder al balanceador de cargas utilizando la dirección IP pública.
   - Simular una carga utilizando una herramienta como `ab`.

## 📜 Documentación

### 📑 Guía de Configuración

1. **Crear una regla de firewall**: Permite las verificaciones de estado desde rangos IP específicos.
2. **Configurar NAT con Cloud Router**: Permite que las instancias envíen tráfico saliente a través de Cloud NAT.
3. **Crear una imagen personalizada**: Configurar un servidor web y crear una imagen para su uso en grupos de instancias.
4. **Configurar plantillas y grupos de instancias**: Crear plantillas de instancias y definir grupos de instancias administrados.

### 📘 Manual de Usuario

Consulta el archivo `manual_de_usuario.pdf` en la carpeta `docs` para obtener una guía detallada sobre cómo utilizar y gestionar el balanceador de cargas.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, sigue los siguientes pasos:

1. Haz un fork del proyecto.
2. Crea una nueva rama (`git checkout -b feature/nueva_funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`).
4. Sube tus cambios (`git push origin feature/nueva_funcionalidad`).
5. Abre un Pull Request.

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## 📞 Contacto

Para cualquier pregunta o problema, por favor, contacta con (https://www.linkedin.com/in/raziel-jimenez-mendoza/).

## **Requisitos:**

* Una cuenta de Google Cloud.
* Acceso a la línea de comandos de Google Cloud.
```
