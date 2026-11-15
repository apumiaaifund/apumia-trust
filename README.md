<p align="center"><img src="assets/logo.svg" alt="logo" width="400"></p>

![PROVEN](https://img.shields.io/badge/PROVEN-38%20passed-brightgreen)

# Apumia Trust

**Ed25519 Trust Stamp для LLM. Регулятор проверяет подпись публично, не заходя в систему банка.**

---

## За 30 секунд

**Что это:** PUMA фильтрует вход (injection, PII), BEE проверяет выход (утечки), Trust Authority выдаёт Ed25519-подписанный Trust Stamp с SHA-256 audit hash.

**Кому:** CCO / MLRO / CTO в банке и финтехе (AIFC, MAS, PDPL).

**Почему сейчас:** MAS требует независимой проверки. Self-attestation не считается. Trust Stamp — артефакт, который регулятор проверяет сам, без доступа к банку.

**Что доказано:** 38 passed. Реальная подпись Ed25519, tamper detection (hash_mismatch на подмену), публичная верификация через /v1/verify и standalone_verify.py. apumia prove → PROVEN.

**Чего не доказано (честно):** 0 клиентов. ФСТЭК/152-ФЗ — не в коробке. NER (spacy) — опционален.

---

## Оффер

PoC $15–25K: полный код, 38 тестов, 30 дней интеграции.

**Следующий шаг:** 20-минутный звонок — покажу живую верификацию подписи, без слайдов.

---

## GitHub

- **Private code:** apumiaaifund/apumia-trust
- **Public demo:** apumiaaifund/apumia-trust-demo

## License

MIT
