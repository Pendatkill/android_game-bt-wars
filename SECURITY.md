# Seguridad

BT Wars no tiene acceso a internet y no guarda los dispositivos que detecta.

Si encuentras un problema de seguridad, no abras una *issue* pública: usa **Security → Report a vulnerability** en este repositorio.

Para comprobar que tu APK es el oficial, compara su huella SHA-256 con la publicada en la release:

```bash
sha256sum BT-Wars-v4.2.apk                              # Linux / macOS
Get-FileHash .\BT-Wars-v4.2.apk -Algorithm SHA256       # Windows (PowerShell)
```

El certificado de firma debe ser `CN=BT Wars, O=pendatkill-dev, C=ES`.
