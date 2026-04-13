# Зашифрованные файлы

## omniroute-setup.enc

Зашифрованная версия HTML-инструкции по установке OmniRoute.

### Расшифровка

```bash
openssl enc -aes-256-cbc -d -pbkdf2 -iter 10000 -in omniroute-setup.enc -out omniroute-setup.html -k "secure_password_for_encryption"
```

**Пароль:** `secure_password_for_encryption`

### Содержание

Файл содержит HTML-инструкцию по установке и настройке OmniRoute и Claude Code.