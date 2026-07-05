# Changelog

## v6.12.0-fixed (2026-07-05)

### Bugs corregidos
- 🐛 **Nombres con paréntesis anidados**: El extractor de nombres de serie ahora maneja correctamente paréntesis dentro de paréntesis (ej: "Show (Season 2 (Extended))")
- 🐛 **Directorio de datos no creado**: El servicio ahora crea ADDON_DATA antes de guardar metadata si no existe
- 🐛 **listdir no compatible**: remove_from_library ahora maneja tanto tuple como lista plana de xbmcvfs.listdir()
- 🐛 **.strm obsoletos**: Ahora se actualizan automáticamente si la URL del streaming cambia
- 🐛 **Numeración de episodios inconsistente**: Añadido fallback que extrae el número de episodio del filepath cuando el label no lo contiene

### Mejoras
- 🚀 Refresco automático de URLs en .strm existentes
- 🚀 Detección más robusta de nombres de serie
