# tas_13-2026-USM
repo para tas grupo 13 usm 2026 sede conce 

#  Estructura

 ***- VM 206 - Base de Datos y CMS***
 - MariaDB
 - Wordpress + WooCommerce + Apache
 - Red Interna: `10.33.199.106`
 - 
 
 ***- VM 250 - DNS***
 - Bind9
 - Red Interna: `10.33.199.109`
 - Zona: `tas13.local`
  
 
 Flujo:  
`Cliente → DNS (VM 206) → CMS (VM 250) → BD (VM 250)`

# Implementado
- DNS autoritativo para `tas13.local`
- 
