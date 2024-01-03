# GitHub Kullanıcı Adı Kontrolü
Bu Python script'i, belirli bir isim için GitHub'da boşta olan kullanıcı adlarını bulmayı amaçlamaktadır. GitHub'un API sınırlamalarına ve kullanım koşullarına dikkat ederek kullanılmalıdır.

## Nasıl Kullanılır
1. İlk olarak, `requests` kütüphanesini yüklemek için terminal veya komut istemcisine şu komutu yazın:

    ```bash
    pip install requests
    ```
2. Ardından, `main.py` dosyasındaki `ad` değişkenini istediğiniz isme ayarlayın.

    ```python
    ad = "YAZBURAYA"
    ```
3. Son olarak, terminal veya komut istemcisinde şu komutu çalıştırarak betiği başlatın:

    ```bash
    python main.py
    ```
    
## Notlar
- Kullanıcı adı kontrolü sırasında her bir kullanıcı adı için 60 saniye beklenir. Bu, GitHub'un kullanım koşullarına uymaya yönelik bir önlemdir.
- Eğer GitHub API kullanılıyorsa veya belirli sınırlamalara tabi bir hizmet varsa, bekleme sürelerini düzenleyebilirsiniz.
- Bu tür otomatik kullanıcı adı kontrolü, GitHub Kullanım Koşulları'na uygun olmalıdır. GitHub API kullanımı için gereken doğrulama işlemlerini gözden geçirin.

Umarım bu açıklama size yardımcı olur!
