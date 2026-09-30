# Blake3-hashing
Secure password storage in Python. Per-user salt defeats rainbow tables, Argon2id resists brute force, and a rotatable BLAKE3 keyed pepper protects against database-only leaks. Includes a FastAPI reference app (register/login, rate limiting, SQLAlchemy) and pepper-rotation tooling.
