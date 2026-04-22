MATCH (p:Persona)-[:PARTICIPA_EN]->(pr:Proyecto)
RETURN pr.nombre AS Proyecto, count(DISTINCT p) AS TotalPersonas