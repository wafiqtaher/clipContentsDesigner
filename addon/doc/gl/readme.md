# Clip Contents Designer #

*	Autores: Noelia Ruiz Martínez.
*	Descargar [versión estable][1]
*	Descargar [versión de desenvolvemento][2]

Este complemento úsase para engadir texto ó portapapeis, que pode ser útil
cando queras unir seccións de texto listas para pegarse xuntas.  O contido
do portapapeis tamén pode limparse.

## Ordes de teclado ##
*	NVDA+windows+c: engade o texto seleccionado, os caracteres braille Unicode
  que representan obxectos MathML, ou a cadea que se marcou co cursor de
  revisión, ao portapapeis.
*	NVDA+windows+x: Limpa o contido do portapapeis.
*	NVDA+windows+f9: Marca a posición actual do cursor de revisión como o comezo do texto a engadir ó portapapeis. Se utilizas NVDA+F9, o texto non se engadirá.
*	 Non asignado: Copia (ou curta) ao/do portapapeis, coa posibilidade de seren preguntado por unha confirmación anterior.

Nota: as ordes anteriores poden cambiarse dende o menú NVDA, submenú
Preferencias, diálogo Xestos de Entrada, categoría Revisión de Texto.

## Menú Preferencias ##
**	Opcións do Clip Contents Designer: permite poñer un separador que poda usarse para atopar os segmentos de texto una vez que todo o texto sexa pegado.
Tamén é posible escoller se o texto engadido se anexará ou se anteporá, se hai accións dispoñibles (engadir, valdeirar portapapeis, emular copiar e emular cortar) deberían realizarse inmediatamente ou despois dunha confirmación, e se hai confirmacións se preguntará só se o texto está contido no portapapeis.

Notas:

*	A orde anterior pódese cambiar dende o menú NVDA, submenú Preferencias,
  diálogo Xestos de Entrada, categoría Configuración.
*	Non se deberían de solicitar confirmacións cando siga aberto unha Caixa de
  mensaxe do NVDA. Nesos casos, as accións realizaranse inmediatamente

## Cambios para 6.0

*	 Engadidas opcións para escoller se as accións dispoñibles se deberían realizar despois da confirmación.
*	Engadíronse ordes Emular copiar e Emular cortar, qué poderían asignarse dende o diálogo Xestos de Entrada.
*	 Engadido un diálogo para configurar as funcionalidades Emular copiar e Emular copiar na instalación. Esto permite engadir as ordes control+c e control+x para copiar e curtar, e ser preguntado se queres reemplazar os contidos do portapapeis ao premer estos atallos de teclado.
*	Arranxada a documentación para script_add (Windows+NVDA+c).

## Cambios para 5.0 ##

*	A presentación visual do diálogo mellorouse, engadíndose á aparenza dos
  diálogos amosados no NVDA.
*	Requírese do NVDA 2016.4 ou posterior.

## Cambios para 4.0 ##
*	As opción do complemento adminístranse dende a configuración do NVDA, así
  que os perfís estándar pódense usar para gardar diferentes separadores, e
  non é necesario copiar as opcións para importalas na reinstalación.
*	Agora é posible escoller se o texto engadido se anexará ou se anteporá,
  usando a casilla de verificación Engadir texto antes de clip data dende o
  diálogo Opcións do Clip Contents Designer.

## Cambios para 3.0 ##
*	Pódese engadir a representación braille de obxectos MathML ó portapapeis
  se MathPlayer está instalado.
*	Se non se puxo un separador, porase una soa liña entre os segmentos de
  texto engadido.
*	Pódese asignar un atallo de teclado para abrir o diálogo de opcións do
  Clip Contents Designer .
*	Engadida unha caixa de verificación no diálogo de opcións, para escoller
  se o separador se debería copiar para seren importado cando se reinstale o
  complemento.

## Cambios para 2.0 ##
*	Pódense usar caracteres Hindi como o separador entre contidos engadidos.

## Cambios para 1.0 ##
*	Versión inicial.

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=ccd

[2]: http://addons.nvda-project.org/files/get.php?file=ccd-dev
