# API: CSCH-PYTA-RefreshToken

## 📌 Endpoint `/refresh-token`
- **Método:** `POST`
- **Descripción:** Genera un nuevo token de acceso.
- **Parámetros:**
  - `refreshToken` (string): Token de actualización válido.
- **Respuesta:** Devuelve un nuevo `accessToken`.

## 🔗 Ejemplo de solicitud
```http
POST /refresh-token
Content-Type: application/json

{
  "refreshToken": "abcd1234"
}
