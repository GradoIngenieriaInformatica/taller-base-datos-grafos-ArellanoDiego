MATCH (e:Empresa {nombre: 'TechCorp'})<-[:TRABAJA_EN]-(p:Persona)-[:USA]->(t:Tecnologia)
RETURN DISTINCT t.nombre AS Tecnologia