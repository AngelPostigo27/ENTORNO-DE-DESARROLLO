# ENTORNO-DE-DESARROLLO
GitHub de entornos de desarrollo de Ángel Postigo Rodríguez

DIAGRAMA DE ACTIVIDADES:
  En este diagrama se tendrá en cuenta que el cliente puede tener o no tener mascota , ya que puede estar registrado en la base de datos de la clínica previamente. Después, el cliente podrá hacer o no consultas, las cuales serán rellenadas posteriormente por el propio veterinario adjuntando el tipo del que precise la consulta. El veterinario podrá prescribir los tratamientos y podrá registrar los diagnosticos de las mascotas, por lo que para prescribir a los tratamientos y poder conocer el coste del tratamiento y el registro del medicamento asociado al tratamiento, se llamará a la clase tratamiento, la cual tiene como atributo el medicamento que necesita y el precio de este, para que después la mascota pueda recibir el tratamiento pertinente.

  DIAGRAMA DE ACTIVIDADES:
    Para el siguente diagrama se tendrá primero en cuenta si el cliente tiene o no mascota y si quiere realiazar o no una consulta. Si este desea realizar una consulta, registrada y elpasaremos al veterinario el cual puede registrar el diagnóstico o prescribir el tratamiento. Tras la realización de cada opcion se tendrá en cuenta si se ha terminado la acción o no para poder seguir realizando las actividades que se muestran. Si el veterinario calcula el costo del tratamiento y lo registra, la mascota recibirá su tratamiento correspondiente y podrá terminar la accion o registrar otro tratamiento distinto o prescribir otro tratamiento diferente.


  DIAGRAMA DE SECUENCIA:
    El cliente puede realizar la consulta necesaria, por lo que si se realiza, la consulta quedará registrada y hecha una vez haya pasado hacia el veterinario, el cual puede prescribir algún tratamiento o registrar algún diagnóstico que tenga la mascota del cliente.
