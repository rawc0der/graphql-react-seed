## INF CANVASES Model Structure
- [User]
- [User]

- [Room] {name, canvas}    (Room and Canvas form a single superType)
-- [Canvas] {spots}
-=- [Spot] {position(X,Y), Open?, drawings}
----
--=- [Drawings] 
---=-  *position, author, [comments], bitmap64, skore, meta






apollo schema:publish --endpoint=http://localhost:4000 --key="service:infinite-canvases:y9RSaNkiy7AuENcopZXB4A"