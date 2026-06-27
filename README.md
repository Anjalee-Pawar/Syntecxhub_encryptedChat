
encrypted-chat/
├── crypto/
│   ├── __init__.py
│   └── encryption.py       ← AES + DES cipher classes, PBKDF2 key derivation
├── server/
│   └── server.py           ← Multi-client TCP server (threaded)
├── client/
│   └── client.py           ← Interactive terminal client
├── logs/
│   └── chat.log            ← Auto-generated message log
├── protocol.py             ← Wire protocol (HELLO/ACK/MSG/SYS/BYE)
├── logger.py               ← Thread-safe file + stdout logger
├── test_encryption.py      ← Self-test (run this first!)
├── demo.py                 ← Automated demo (no terminal needed)
└── requirements.txt# Syntecxhub_encryptedChat