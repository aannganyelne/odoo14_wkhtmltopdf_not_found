# odoo14 wkhtmltopdf Not Found
Mengatasi masalah error wkhtmltopdf not found, padahal wkhtmltopdf sudah terinstall di Debian 11

Jalankan command:

```sh
$ which wkhtmltodpf
```
Contoh output: `/usr/bin/wkhtmltopdf`  copy path ini.

* Masuk ke Debug Mode
* Masuk ke Settings -> Customization -> Parameters -> System Parameters
* Search `webkit_path` jika tidak ditemukan Klik `Create`
* Isikan Key: `webkit_path`
* Isikan Value: `/usr/bin/wkhtmltopdf`  (value sesuai hasil dari command `which wkhtmltopdf`
* Simpan lalu refresh
