# Flonmundi
Practica de examen usando florimundo como ejemplo
JERAQUIA

- DIRECCION
-- CONFIDERENCIAL
-- LIBRE
- CALIDAD
- OPERATIVA
-- PRODUCCION
-- LOGISTIC
  - COMERCIAL MARKETING
- LEGAL

- El  criterio de jeraquia ha sido mediante seacciones de la logica de negocio y un segun de criterio sobre los paraisos del documento.




 POSIBLE ETIQUETAS
 SEDE: espana,kenia,paises_bajos,bolombia,global
 PRODUCTO: lirio,rosa,clavel,orquidea
 TIPO_DOCUMENTO: Fecha_tecnica, Certificado, Contrato, Guía-tecnica
 TEMPORADA: Verano,navidad,invierno
 ESTADO: borrador,en_revision, en_proceso,archiva,enviado,publicado,rechazado


 PLANTILLA METADATOS
 ---
codigo: FR_ES_2026_001
titulo: Ficha tecnica Rosa del Desierto
sede: espana
version: 1.1
rèponsables: Juan Gonzalez
fecha_creacion: 01/05/2026
fecha_revision:02/05/2026
estado: Aprobado
palabra_clave: [rosa,flor, semillerodeoro,sus tipoC}
 ---


NOMENCLATURA
FM_ESROS_2026_001.PDF
He usado  la inicial de la empresa
la sede, el codigo de producto RO-S-Rosa
año y el numero de la version

FM_CLLIR_2025_034.PDF

PEDIDOS
PEDFM_ES01052026_89878_0534.PDF
PED pedido+ FM florimendi +Sede+ Fecha+ n ºcliente + nºpedido

FLUJO DE TRABAJO 
- Issue para pedir documento o modificacion-- tecnico
- Crea una rama para el documento segun tipo--- nuevas- rosas
- edita el docuemnto por parte de del semillero
- Abre un pull request (peticion de aprobacion)
-  El verificador/responsable aprueba y hace rerge
-  Le colula de la etiqueta de publicado y lo coloca en la carpeta de documentos publicos.
-  estado inicial del documento
-  que actor tiene que hacer
-   que tiene que hace (tarea,condiciones,plazo)
-   y cual seria el estado siguiente

Estados del docuemntos- ciclo de vida de docuemnto
BORRADOR
ENREVISION
APROBADO 
ARCHIVADO
ELIMINADO (no llegaria a ponerse)

                              Director                                reponsablearea                   editor                           externo
Pedido:                       VER                                     VER/EDITAR                           CREAR                           NADA
Guia tecnica                  VER                                       VER                                CREAR /EDITAR                     VER 
contrato                       EDITAR (Aprobar)                          VER                                    No                           No
