# 7-2-Cloud SQL Concepts 

[Typy baz](https://cloud.google.com/products/databases)

```
Scale insurance - ubezpieczenie na dużą skalę (możesz rozpocząć produkcję od małej instancji i nie musisz zmieniać architektury wraz z rozwojem aplikacji):
- Cloud Spanner
- Cloud Bigtable
- Cloud Firestore

NO Scale insurance:
- Cloud SQL
- Firebase Realtime Database
- Cloud Memorystore
```
```
Data distrybution (regional and global):
- Cloud Spanner 
- Cloud Bigtable
- Cloud Firestore

Data distrybution (zonal):
- Cloud SQL
- Firebase Realtime Database
- Cloud Memorystore
```
```
Replica consistency (Spójność repliki) - strong / eventual
Multi-primary
Transactions (strong consistency)
Joins and complex queries
Ultra low latency (microsecond or single-digit ms)
