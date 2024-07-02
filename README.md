kitap barkodlarini okuyup xlsx formatında kitap bilgileri ile kaydeden basit bir python betiği

### Özellikleri

* Girilen barkodun kitap adı, yazarı, yayınevi, iskonto değeriyle birlikte xlsx formatında kaydeder.
* Kullanılan xlsxwriter kütüphanesi sadece xlsx formatında yeni bir dosya oluşturabilmektedir.(dosyadan okuma özelliği yoktur)

### Programın çalıştırılması için gerekenler
* python 2.x
* pip
* virtualenv

### Kurulum (Linux)
```bash
git clone https://github.com/kodilay/barkod-oku.git
virtualenv barkod-env
source barkod-env/bin/activate
pip install -r requirements.txt
```
### Programin calistirilmasi
```python
python barkod.py
```
