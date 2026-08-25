# Etapa A · Levantar y reconocer la aplicación

Sigan las instrucciones de [`starter/README.md`](./starter/README.md) y levanten:

1. `mock-identity` en `9000`;
2. `reservapp-api` en `8081`;
3. `gateway` en `8080`;
4. `client` en `5500`.

No modifiquen código todavía.

## Evidencia

En el README del grupo registren:

- los cuatro componentes levantados;
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
- qué rol conceptual cumple cada uno;
- una captura o salida que demuestre que ReservApp está operativa.
![alt text](image-4.png)

---

# Etapa B · “Continuar con Google” vs “Conectar Google Drive”

Antes de probar ReservApp, relacionen el laboratorio con algo cotidiano.

### Caso 1 · Continuar con Google

Una aplicación permite reconocer al usuario usando su identidad Google.

Preguntas:

1. ¿La aplicación recibe la contraseña de Google?
2. ¿Qué problema principal estamos resolviendo?
3. ¿Qué papel cumple Google?
4. ¿Cómo se relaciona este caso con OIDC?

### Caso 2 · Conectar Google Drive

El usuario ya inició sesión, pero ahora una aplicación desea abrir o guardar archivos en Drive.

Preguntas:

1. ¿El login anterior entrega automáticamente acceso al Drive?
2. ¿Qué recurso protegido aparece ahora?
3. ¿Por qué hace falta autorización adicional?
4. ¿Cómo se relaciona este caso con OAuth2?

Conclusión esperada:

```text
reconocer quién eres ≠ obtener permiso para usar otro recurso
```

---