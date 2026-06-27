# 🚀 Guía de Instalación Completa

## Tabla de Contenidos
1. [Requisitos previos](#requisitos-previos)
2. [Instalación rápida](#instalación-rápida)
3. [Instalación detallada](#instalación-detallada)
4. [Verificación](#verificación)
5. [Solución de problemas](#solución-de-problemas)

---

## ✅ Requisitos Previos

### Hardware:
- Computadora o dispositivo móvil con cámara web
- Mínimo 2GB de RAM
- Procesador dual-core
- Conexión a Internet (para descargar las CDNs)

### Software:
- **Navegador**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **Sistema Operativo**: Windows 10+, macOS 10.13+, Linux, iOS 14.5+, Android 9+

### Permisos:
- Acceso a la cámara web
- Acceso a almacenamiento local (para descargar marcador)

---

## ⚡ Instalación Rápida (5 minutos)

### Opción A: Sin línea de comandos (MÁS FÁCIL)

1. **Descarga el proyecto**
   - Ve a: https://github.com/danielmorales0919-stack/acta9dejulio
   - Haz clic en `Code` → `Download ZIP`
   - Descomprime la carpeta

2. **Abre la aplicación**
   - Navega a la carpeta descomprimida
   - Haz doble clic en `index.html`
   - Se abrirá automáticamente en tu navegador

3. **Autoriza la cámara**
   - Cuando se te pida, haz clic en "Permitir"
   - ¡La aplicación está lista!

---

### Opción B: Con Node.js (Recomendado para desarrollo)

```bash
# 1. Descargar proyecto
git clone https://github.com/danielmorales0919-stack/acta9dejulio.git
cd acta9dejulio

# 2. Instalar dependencias
npm install

# 3. Ejecutar servidor
npm start

# Se abrirá automáticamente en: http://localhost:8000
```

---

### Opción C: Con Python (Sin Node.js)

```bash
# Python 3 (versión nueva)
python -m http.server 8000

# Python 2 (versión antigua)
python -m SimpleHTTPServer 8000

# Abre en el navegador: http://localhost:8000
```

---

## 📚 Instalación Detallada

### Para Windows

#### Método 1: Sin instalar nada

```
1. Descarga ZIP del proyecto
2. Haz clic derecho → Extraer aquí
3. Abre la carpeta
4. Doble clic en index.html
5. ¡Listo!
```

#### Método 2: Con Node.js

```bash
# Descargar Node.js desde: https://nodejs.org/
# Instalar (sigue el instalador)
# Abrir PowerShell o CMD

cd C:\Users\TuUsuario\Descargas\acta9dejulio
npm install
npm start
```

#### Método 3: Con Python

```bash
# Windows 10/11 ya tiene Python 3 en Microsoft Store
# O descarga desde: https://www.python.org/

cd C:\Users\TuUsuario\Descargas\acta9dejulio
python -m http.server 8000
```

---

### Para macOS

#### Método 1: Sin instalar nada

```bash
# Desde Terminal:
cd ~/Downloads/acta9dejulio
open index.html
```

#### Método 2: Con Node.js

```bash
# Instalar Homebrew (si no lo tienes)
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Instalar Node.js
brew install node

# Ejecutar proyecto
cd ~/Downloads/acta9dejulio
npm install
npm start
```

#### Método 3: Python (ya incluido en macOS)

```bash
cd ~/Downloads/acta9dejulio
python3 -m http.server 8000
```

---

### Para Linux

#### Ubuntu/Debian

```bash
# Actualizar sistema
sudo apt update && sudo apt upgrade

# Instalar Node.js (opcional)
sudo apt install nodejs npm

# Descargar proyecto
git clone https://github.com/danielmorales0919-stack/acta9dejulio.git
cd acta9dejulio

# Instalar y ejecutar
npm install
npm start
```

#### Con Python

```bash
cd acta9dejulio
python3 -m http.server 8000
```

---

### Para Dispositivos Móviles

#### iOS (iPhone/iPad)

1. **Opción 1: Safari directo**
   - Abre Safari
   - Ve a: `http://[tu-ip-local]:8000`
   - La IP la ves en la terminal cuando ejecutas el servidor

2. **Opción 2: Compartir pantalla**
   - Corre el servidor en tu PC/Mac
   - Desde iPhone, abre Safari en la misma red WiFi
   - Accede a la IP que se muestra

#### Android (teléfono/tablet)

1. **Opción 1: Chrome directo**
   - Abre Chrome
   - Ve a: `http://[tu-ip-local]:8000`
   - Permite acceso a la cámara

2. **Opción 2: GitHub Pages**
   - Si tienes el repo en GitHub
   - Habilita GitHub Pages en Settings
   - Accede desde tu móvil

---

## ✔️ Verificación

### Checklist post-instalación:

```
☐ La aplicación se abre en el navegador
☐ Ves el header "ACTA 9 DE JULIO"
☐ Se muestra el panel de control inferior
☐ El indicador de marcador está visible (punto rojo/verde)
☐ Puedes hacer clic en "Iniciar AR"
☐ Se pide permiso de cámara
☐ Después de permitir, ves el video de la cámara
☐ Puedes hacer clic en "Descargar Marcador"
```

Si todos los puntos están ✓, ¡está funcionando perfectamente!

---

## 🐛 Solución de Problemas

### "No se puede descargar"

**Problema**: No puedo descargar el ZIP de GitHub

**Soluciones**:
```bash
# Usa Git en su lugar
git clone https://github.com/danielmorales0919-stack/acta9dejulio.git

# O descarga manualmente desde:
https://github.com/danielmorales0919-stack/acta9dejulio/archive/refs/heads/main.zip
```

---

### "El archivo no abre"

**Problema**: Hago doble clic en index.html pero no abre

**Soluciones**:
```
1. Haz clic derecho en index.html
2. Selecciona "Abrir con"
3. Elige tu navegador (Chrome, Firefox, etc.)
4. Si no aparece, busca el navegador manualmente
```

---

### "Node.js no reconocido"

**Problema**: `npm: no se encuentra el comando`

**Soluciones**:
```bash
# 1. Verifica que está instalado
node --version
npm --version

# 2. Si no aparece, descarga e instala desde:
https://nodejs.org/

# 3. Reinicia la terminal/PowerShell después de instalar
```

---

### "Puerto 8000 ya está en uso"

**Problema**: `Error: listen EADDRINUSE :::8000`

**Soluciones**:
```bash
# Usa otro puerto
npm start -- --port 3000
# O
python -m http.server 3000

# Luego accede a: http://localhost:3000
```

---

### "Permiso de cámara denegado"

**Problema**: La cámara no funciona

**Soluciones Windows**:
```
1. Abre Configuración → Privacidad
2. Cámara → Permitir que las aplicaciones usen la cámara
3. Busca tu navegador y habilita
4. Reinicia el navegador
```

**Soluciones macOS**:
```
1. Abre Preferencias del Sistema
2. Seguridad y privacidad
3. Cámara
4. Marca el navegador
5. Reinicia el navegador
```

**Soluciones Linux**:
```bash
# Verifica permisos de dispositivo
ls -la /dev/video0

# Si no tienes acceso, agrega tu usuario al grupo
sudo usermod -a -G video $USER
# Cierra sesión y vuelve a abrir
```

---

### "HTTPS requerido en iOS"

**Problema**: iOS solo permite cámara en HTTPS

**Soluciones**:
```
1. Descarga desde GitHub Pages (es HTTPS)
2. O configura un certificado SSL local
3. O usa ngrok para crear HTTPS:
   ngrok http 8000
```

---

### "Aplicación lenta"

**Problema**: Mucho lag o bajo FPS

**Causas y soluciones**:
```
1. Demasiadas pestañas abiertas
   → Cierra otras pestañas

2. Poco espacio en RAM
   → Reinicia el dispositivo

3. Cámara con resolución muy alta
   → Reduce en configuración del navegador

4. Mala iluminación
   → Mejora la iluminación del ambiente

5. Dispositivo muy antiguo
   → Actualiza el navegador o dispositivo
```

---

### "Marcador no se detecta"

**Problema**: La app abre pero no detecta el marcador

**Soluciones**:
```
1. Descarga el marcador desde la app
2. Imprímelo en tamaño A4
3. Asegúrate que está bien iluminado
4. Mueve la cámara lentamente
5. Acércate a 30-50 cm del marcador
6. Evita reflejos en el papel

Alternativa: Abre el marcador en otra pantalla
(tablet, laptop) en lugar de imprimir
```

---

## 🎯 Primeras Pruebas

Después de instalar, sigue estos pasos para verificar que todo funciona:

### Test 1: Interfaz básica
```
1. Abre index.html
2. Verifica que se carga completamente
3. Presiona F12 para abrir Developer Tools
4. Mira la pestaña "Console" para errores
5. Si no hay errores en rojo, ¡OK!
```

### Test 2: Cámara
```
1. Haz clic en "Iniciar AR"
2. Permite acceso a cámara
3. Deberías ver el video de la cámara
4. El indicador pasa de rojo a verde
```

### Test 3: Marcador
```
1. Descarga el marcador
2. Imprímelo o abre en otra pantalla
3. Apunta la cámara al marcador
4. El indicador debe volverse completamente verde
5. Deberías ver el Acta en 3D
```

---

## 📞 Soporte Técnico

Si tienes problemas que no están aquí:

1. **GitHub Issues**: https://github.com/danielmorales0919-stack/acta9dejulio/issues
2. **Comprueba tu navegador**: https://caniuse.com/webxr
3. **Verifica permisos**: Configuración → Privacidad → Cámara
4. **Reinicia todo**: Navegador, dispositivo, servidor

---

## ✅ Verificación Final

```bash
# Para verificar que todo está bien, ejecuta:

# 1. Verifica Node (si lo usas)
node --version  # Debería ser v14+

# 2. Verifica npm (si lo usas)
npm --version   # Debería ser v6+

# 3. Verifica Python (alternativa)
python --version  # Debería ser Python 3

# 4. Verifica conectividad
ping google.com  # Debe tener respuesta
```

---

¡Listo! Tu aplicación de Realidad Aumentada está completamente instalada y funcionando. 🚀🇦🇷
