# webshells-archive

📁 PHP File Manager — fdrfpp.4
PHP File Manager (fdrfpp.4) is a lightweight and self-contained web-based file manager written in PHP. It provides a fast and functional interface for managing files and directories directly through the browser, with built-in support for editing, uploading, archiving, and even executing PHP and SQL commands.

✨ Key Features
🔐 Authentication System
Login with username/password and optional cookie-based session handling.

📝 Inline Code Editor
Integrated syntax-highlighted code editor using EditArea.

📁 File & Folder Management
Create, rename, delete, upload, download, compress (tar.gz), and decompress files and directories.

🧰 Built-in PHP and SQL Console
Run custom PHP or SQL commands from within the interface.

📊 PHP Environment Info
View phpinfo(), PHP version, and loaded config paths.

🌍 Multilingual Support
Interface available in English, Russian, German, French, and Ukrainian.

🛠 Configuration
All core settings (e.g., login credentials, language, feature toggles) are stored in the script’s JSON-config section at the top. You can customize:

Admin username/password

Cookie name and expiration

Enabled/disabled modules

SQL connection info

Display preferences

⚠️ Security Notice
This script provides deep access to server files and should not be exposed to the public in production environments. Please:

Change default credentials immediately

Enable HTTPS when serving it

Restrict access with firewall or IP whitelisting

Use only in secure, isolated, or internal environments

🧪 Ideal for:
Remote file system control on personal servers

Educational use, sandbox management

Emergency access panels for sysadmins

