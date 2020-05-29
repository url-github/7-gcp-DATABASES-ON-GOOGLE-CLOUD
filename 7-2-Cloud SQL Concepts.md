# 7-2-Cloud SQL Concepts 

To zarządzalna usługa do hostowania w modelu PaaS:
- MySQL
- PostgreSQL
- SQL Server

Keywords:
- Replications options / read replicas - Cloud SQL zapewnia możliwość replikacji instancji głównej do jednej lub więcej replik odczytu. Replika odczytu jest kopią wzorca, która odzwierciedla zmiany w wystąpieniu wzorca w prawie czasie rzeczywistym.

[Istnieją 4 ścieżki możliwej repliki](https://cloud.google.com/sql/docs/mysql/replication)

- Backups:
  - [Automated backups] co 24h w wybranym oknie 4h.
  - [On-demand backups czyli na żądanie](https://cloud.google.com/sql/docs/mysql/backup-recovery/backups#on-demand-backups)
  
- [Przywracanie instancji](https://cloud.google.com/sql/docs/mysql/backup-recovery/restore):
  - Restore
  - Point in time Restore



