MATCH (e:Empresa {nombre: "TechCorp"})<-[:TRABAJA_EN]-(p:Persona)-[:USA_TECNOLOGIA]->(t:Tecnologia)
RETURN DISTINCT t.nombre AS Tecnologia