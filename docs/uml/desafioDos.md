
---
#### **Desafío 2 - Sistema de compras y ventas en línea**
---

<p style="text-align: justify;">
En el siguiente desafío, tendremos la oportunidad de poder desarrollar la base del código para un sistema de compras y ventas online, tomando en cuenta los siguientes puntos:
</p>

* El usuario del sistema consta de los siguientes atributos: id, nombre, correo, esAdmin, password.
* Los productos poseen los siguientes atributos: id, nombre, descripcion, cantidad, status, categoría.
* Un usuario puede ser vendedor y además ser comprador.
* Los compradores realizan transacciones y los vendedores realizan el seteo de productos.

<p style="text-align: justify;">
Se debe realizar el diagrama de clases que modele el problema y además se debe escribir el código en Java, obtenido del diagrama de clases que acabamos de diseñar.
</p>

---
#### **Solución**
---
##### Parte 1:
&nbsp;
<center>![casosUso](img/test00201.png)</center>
&nbsp;

##### Parte 2:

###### Clase Usuario:

```Java
package cl.desafiolatam.uml.desafio2

public class Usuario {
    private Long id;
    private String nombre;
    private String correo;
    private String password;
    private boolean esAdmin;

    public Usuario(Long id, String nombre, String correo, String password, boolean esAdmin) {
        this id = id;
        this nombre = nombre;
        this correo = correo;
        this password = password;
        this esAdmin = esAdmin;
    }

    public void setNombre(String nombre) {
        // TODO implementar aquí.
    }

    public void setCorreo(String correo) {
        // TODO implementar aquí.
    }

    public void setPassword(String password) {
        // TODO implementar aquí.
    }

    public void setEsAdmin(void boolean opt) {
        // TODO implementar aquí.
    }

    public String getNombre() {
        // TODO implementar aquí.
        return "";
    }

    public String getCorreo() {
        // TODO implement here
        return "";
    }

    public String getPassword() {
        // TODO implement here
        return "";
    }

    public boolean getEsAdmin() {
        // TODO implement here
        return false;
    }

}

```

###### Clase Comprador:

```Java
package cl.desafiolatam.uml.desafio2


public class Comprador extends Usuario {
    public Comprador(Long id, String nombre, String correo, String password, boolean esAdmin) {
    	super(id, nombre, correo, password, esAdmin);
    }

    public Producto getProducto() {
        // TODO implementar aquí.
        return null;
    }

}
```
###### Clase Vendedor:

```Java
package cl.desafiolatam.uml.desafio2

public class Vendedor extends Usuario {

    public Vendedor(Long id, String nombre, String correo, String password, boolean esAdmin) {
    	super(id, nombre, correo, password, esAdmin);
    }

    public void setProducto(Producto prod) {
        // TODO implementar aquí.
    }

}
```

###### Clase Transaccion:

```Java
package cl.desafiolatam.uml.desafio2

public class Transaccion {
    public Comprador comprador;
    public Producto producto;

}

```

###### Clase Categoria:

```Java
package cl.desafiolatam.uml.desafio2

public class Categoria {
    private Long id;
    private String nombre;

    public Categoria(Long id, String nombre){
        this id = id;
        this nombre = nombre;
    }

    public void setNombre(void String nombre) {
        // TODO implementar aquí.
    }

    public String getNombre() {
        // TODO implementar aquí.
        return "";
    }

}

```

###### Clase Producto:

```Java
package cl.desafiolatam.uml.desafio2
package cl.desafiolatam.uml.desafio2

public class Producto {
    private int id;
    private String nombre;
    private String descripcion;
    private int cantidad;
    private int status;
    private Categoria categoria;
    private Comprador comprador;
    private Vendedor vendedor;

    public Producto(
        int id, 
        String nombre, 
        String descripcion, 
        int cantidad, 
        int status, 
        Categoria categoría){
        
        this.id = id;
        this.nombre = nombre;
        this.descripcion = descripcion;
        this.cantidad = cantidad;
        this.status = status;
        this.categoria = categoria;
    }

    public void setNombre(String nombre) {
        // TODO implementar aquí.
    }

    public void setDescripcion(String descripcion) {
        // TODO implementar aquí.
    }

    public void setCantidad(int num) {
        // TODO implementar aquí.
    }

    public void setStatus(int status) {
        // TODO implementar aquí.
    }

    public void setCategoría(Categoría cat) {
        // TODO implementar aquí.
    }

    public void setComprador(Comprador comp) {
        // TODO implementar aquí.
    }

    public void setVendedor(Vendedor vend) {
        // TODO implementar aquí.
    }

    public String getNombre() {
        // TODO implementar aquí.
        return "";
    }

    public String getDescripcion() {
        // TODO implementar aquí.
        return "";
    }

    public int getCantidad() {
        // TODO implementar aquí.
        return 0;
    }

    public int getStatus() {
        // TODO implementar aquí.
        return 0;
    }

    public Categoria getCategoría() {
        // TODO implementar aquí.
        return null;
    }

    public Comprador getComprador() {
        // TODO implementar aquí.
        return null;
    }

    public Vendedor getVendedor() {
        // TODO implementar aquí.
        return null;
    }

}

```



