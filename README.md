# Tampermonkey Video URL Gönderme Scripti

Bu script, **tranimeizle.top** web sitesindeki video URL'lerini tespit eder ve Discord kanalınıza gönderir. Script, Mail.ru, Odnoklassniki, Sibnet gibi video platformlarının URL'lerini otomatik olarak algılar ve bunları belirlediğiniz **Discord Webhook**'una iletir.

---

## İçindekiler:
1. [Kurulum Adımları](#kurulum-adımları)
2. [Discord Webhook Nasıl Alınır?](#discord-webhook-nasıl-alınır)
3. [Tampermonkey Kullanımı](#tampermonkey-kullanımı)
4. [Script İzinleri](#script-izinleri)
5. [Script Özellikleri](#script-özellikleri)

---

## Kurulum Adımları

### 1. **Tampermonkey Eklentisini Yükleyin**

Öncelikle, **Tampermonkey** eklentisini tarayıcınıza yüklemeniz gerekmektedir.

- **Google Chrome**: [Tampermonkey - Chrome Web Store](https://chrome.google.com/webstore/detail/tampermonkey/)
- **Mozilla Firefox**: [Tampermonkey - Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)

Yükledikten sonra, eklenti simgesine tıklayarak Tampermonkey’i açın.

---

### 2. **Scripti Yükleyin**

1. [Buraya tıklayın](#) ve scripti kopyalayın.
2. Tampermonkey simgesine tıklayın ve **Dashboard** sekmesine gidin.
3. Sağ üst köşede **"Add a new script"** butonuna tıklayın.
4. Yeni açılan sekmeye kopyaladığınız scripti yapıştırın ve **Save** butonuna basın.

Script artık çalışmaya hazır olacak.

---

## Discord Webhook Nasıl Alınır?

Discord'da video URL'lerini gönderebilmek için **Webhook** oluşturmanız gerekmektedir. Aşağıda adım adım nasıl yapılacağı anlatılmıştır:

### 1. **Discord Sunucusunda Yönetici Olmalısınız**

Webhook oluşturabilmek için sunucuda **yönetici** yetkilerine sahip olmanız gerekir.

### 2. **Kanal Ayarlarına Gitmek**

1. **Discord Sunucusunu Açın** ve webhook göndereceğiniz kanalın üzerine sağ tıklayın.
2. **"Kanal Ayarları"** (Settings) seçeneğine tıklayın.

### 3. **Webhook Oluşturma**

1. Kanal ayarlarında, **Integrations** sekmesine tıklayın.
2. **Webhooks** bölümünü bulun ve **Create Webhook** butonuna tıklayın.

### 4. **Webhook URL'sini Kopyalayın**

1. Webhook’a bir isim verin (örneğin: **Video URL Gönderici**).
2. Mesajların gönderileceği kanal için doğru seçimi yapın.
3. **Webhook URL**'sini kopyalayın.

### 5. **Webhook URL'sini Script'e Ekleyin**

1. Kopyaladığınız **Webhook URL**'sini, scriptteki **customWebhookUrl** alanına yapıştırarak kaydedin.
2. Artık videolar, bu URL üzerinden Discord kanalınıza gönderilecektir.

---

## Tampermonkey Kullanımı

### 1. **Skripti Çalıştırma**

Scripti yükledikten sonra, **tranimeizle.top** gibi uygun bir sayfayı ziyaret edin ve scriptin çalıştığından emin olun. Video URL'leri otomatik olarak algılanacak ve Discord kanalınıza iletilecektir.

### 2. **Script Durumunu Kontrol Etme**

- Script çalışıyorsa, ekranın sağ üst köşesinde **"Script: Açık"** yazısını görmelisiniz.
- Scripti açıp kapatmak için, aynı paneldeki **checkbox**'u kullanabilirsiniz.

---

## Script İzinleri

### **"Bu Alan Adına Her Zaman İzin Ver" Seçeneğini Seçme**

Tampermonkey eklentisi, scriptin çalışabilmesi için **izin istemektedir**. Bu izni şu şekilde verebilirsiniz:

### 1. **İzin Penceresini Görün**
- Scripti ilk kez çalıştırdığınızda, tarayıcınızda **izin isteme** penceresi belirecektir.

### 2. **"Bu Alan Adına Her Zaman İzin Ver" Seçeneğini Seçin**

1. İzin penceresinde **"Bu alan adına her zaman izin ver"** seçeneğini tıklayın.
2. Bu işlem, scriptin belirli bir alan adında (örneğin, **tranimeizle.top**) sürekli olarak çalışmasını sağlayacaktır.

### 3. **Onayla**

İzin verdikten sonra, scriptin sorunsuz şekilde çalışması devam edecektir. Eğer bu adımı atlarsanız, script doğru çalışmayabilir.

---

## Script Özellikleri

- **Video URL Algılama**: Script, **Mail.ru**, **Odnoklassniki**, **Sibnet** ve **Google Drive** videolarının URL'lerini algılar.
- **Discord Webhook Gönderimi**: Video URL'leri, belirlediğiniz Discord kanalına otomatik olarak gönderilir.
- **Kullanıcı Arayüzü**: Scriptin çalışıp çalışmadığını kolayca kontrol edebileceğiniz bir kullanıcı arayüzü bulunur. Ayrıca, scripti açıp kapatabilmeniz için bir kontrol butonu da mevcuttur.
- **Webhook URL Yönetimi**: Kendi **Discord Webhook URL**'inizi girerek, videoların tam olarak istediğiniz kanalınıza iletilmesini sağlayabilirsiniz.

---

## Ekstra İpuçları

- **Webhook URL'sini Güvende Tutun**: Webhook URL'si, yalnızca güvendiğiniz kişilerle paylaşılmalıdır. Bu URL'yi kaybetmemeniz önemlidir, çünkü kötüye kullanıma açık olabilir.
- **Script Performansı**: Script, her 3 saniyede bir sayfayı tarayarak yeni video URL'lerini kontrol eder. Eğer çok fazla video varsa, bu süreyi kısaltabilirsiniz.

---

Eğer bir sorunla karşılaşırsanız, yukarıdaki adımları kontrol ederek sorununuzu çözmeyi deneyin. Eğer hala sorun yaşıyorsanız, **[Discord Sunucusuna](https://discord.gg/Huv44Jy7P7)** katılarak bize ulaşabilirsiniz.

---

**Uyarı**: Bu script sadece **tranimeizle.top** gibi uygun web sitelerinde çalışır ve video URL'lerini izinsiz bir şekilde toplamaz. Kullanım sırasında yerel yasalar ve web sitesi politikalarına dikkat ediniz.
