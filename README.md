# Pennyware - Sistema de Gestión de Pedidos PWA

![Progressive Web App](https://img.shields.io/badge/PWA-Supported-success.svg)
![HTML5](https://img.shields.io/badge/HTML5-Compatible-blue.svg)

# Endpoints de la API
Endpoint	              Método	    Descripción
/api/MCP/pedido	         POST	      Crear nuevo pedido
/api/MCP/pedidos/{id}	   GET	      Obtener pedido por ID
/api/MCP/factura	       POST	      Generar factura
/api/MCP/pagos	         GET	      Listar todos los pagos

##  Descripción
Aplicación web progresiva (PWA) para gestión completa de:
- Pedidos
- Facturación
- Pagos
- Reintento de transacciones fallidas

  ### manifest.json
  ```json
    {
        "name": "Tienda Web",
        "short_name": "Tienda",
        "start_url": "index.html",
        "display": "standalone",
        "background_color": "#ffffff",
        "theme_color": "#2563eb",
        "icons": []
      }

