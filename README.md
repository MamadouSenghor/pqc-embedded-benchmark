# Protocole de benchmark v1

## Messages de test standardisés
1. Message court : "PQC_TEST_2024" (14 bytes)
2. Message moyen : 256 bytes aléatoires
3. Message long : 1024 bytes aléatoires

## Métriques collectées
- Temps (microsecondes)
- Mémoire heap (bytes)
- Taille binaire (bytes)
- Énergie (si disponible)

## Format de logs JSON
{
  "platform": "esp32",
  "algorithm": "ML-DSA-44",
  "operation": "keygen",
  "time_us": 123456,
  "heap_free": 234567,
  "timestamp": "2024-01-01T10:00:00Z"
}