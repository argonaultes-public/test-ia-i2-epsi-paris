## Firefox

Lancer test sur Mozilla Firefox

```bash
export IS_FIREFOX=1 && pytest test_connexion.py
```

## Chrome

Lancer test sur Google Chrome

```bash
unset IS_FIREFOX && pytest test_connexion.py
```