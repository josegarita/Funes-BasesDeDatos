/*Elimina el La columna Nombre de la tabla InstitucionLabora*/ 
alter table funes.institucionlabora drop column Nombre;


/*Crea la tabla Institucion */ 
CREATE TABLE institucion(
	nombre varchar(45)
	);


/*procedimiento para insertar la Institucion */
DELIMITER $$
CREATE DEFINER=`root`@`localhost` PROCEDURE `insertarInstitucion`(pNombre varchar(45))
BEGIN
INSERT INTO `Funes`.`Institucion`
(`nombre`)
VALUES
(pNombre);

END $$
Delimiter ;

/* Agrega la columna Id de la institucion*/
ALTER TABLE Funes.InstitucionLabora ADD 
idInstitucion INT;
