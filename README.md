# Kullanıcı Kayıt Programı

Bu, yeni bir kullanıcı kaydı için hazırlanmış bir programdır. Kullanıcıdan kullanıcı adı ve şifre ister, ardından bu bilgileri bir sözlükte saklar.

## Programı Çalıştırma

Programı çalıştırmak için bilgisayarınızda Python 3.6 veya daha üst bir sürümün kurulu olduğundan emin olun.

1. Proje dosyalarını bilgisayarınıza indirin.
2. Terminali veya komut satırını açın.
3. Program dosyalarının bulunduğu dizine/klasöre gidin.
4. Aşağıdaki komutu kullanarak programı çalıştırın:

```bash
python registration.py
```

## Programı Kullanma

Program çalıştıktan sonra, sizden bir kullanıcı adı ve şifre girmeniz istenecek. Gerekli verileri girip Enter tuşuna basın. Program, güncellenmiş kullanıcı listesini gösterecektir.

## Programın Çalışmasına Bir Örnek

```bash
Sistemde halihazırda kayıtlı kullanıcılar ve şifreleri:
Kullanıcı adı: user1, Şifre: password1
Kullanıcı adı: user2, Şifre: password2
Kullanıcı adı: user3, Şifre: password3
Kullanıcı adı: user4, Şifre: password4
Kullanıcı adı: user5, Şifre: password5

Yeni bir kullanıcı ekleyebilirsiniz.
Yeni kullanıcı adını girin: NEWuser
Yeni kullanıcının şifresini girin: slfvjgdafslbhv`
Yeni kullanıcı NEWuser başarıyla eklendi.

Yeni kullanıcı eklendikten sonraki tüm kullanıcı listesi:
Sistemde halihazırda kayıtlı kullanıcılar ve şifreleri:
Kullanıcı adı: user1, Şifre: password1
Kullanıcı adı: user2, Şifre: password2
Kullanıcı adı: user3, Şifre: password3
Kullanıcı adı: user4, Şifre: password4
Kullanıcı adı: user5, Şifre: password5
Kullanıcı adı: NEWuser, Şifre: slfvjgdafslbhv`
```



## Depo (GitHub) Hakkında

Bu bölüm GitHub deposunda projeyi hızlıca anlamak ve katkıda bulunmak isteyenler için kısa bir özet sağlar.

- Proje: Basit bir kullanıcı kayıt simülasyonu. Mevcut kullanıcıları bir sözlükte tutar ve yeni kullanıcı ekler.
- Python sürümü: Python 3.6 veya üzeri önerilir.

Dosya yapısı (ana öğeler):

- `registration/registration.py` — Programın ana dosyası; kullanıcı başlatma, ekleme ve görüntüleme fonksiyonlarını içerir.
- `tests/test_registration.py` — Basit birim testleri (pytest ile çalıştırılır).
- `pytest.ini` — pytest yapılandırması.

Testleri çalıştırmak için (yerel veya CI):

```powershell
# Proje kök dizininde çalıştırın
python -m pytest -q
```

Katkıda bulunma (kısa):

1. Forklayın ve yeni bir branch oluşturun.
2. Değişikliklerinizi ekleyin ve testleri çalıştırın.
3. Pull request gönderin; kısa bir açıklama ekleyin.


