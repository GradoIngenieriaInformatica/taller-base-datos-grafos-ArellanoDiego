MATCH (e:Empresa {nombre: "DataSoft"})<-[:TRABAJA_EN]-(p:Persona)-[:GESTIONA]->(pr:Proyecto)
RETURN pr.nombre AS Proyecto, p.nombre AS Gestor