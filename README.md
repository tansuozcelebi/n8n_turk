![Banner image](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

# n8n-Turk - Teknik takımlar için işakışları oluştur.

n8n, teknik ekiplere kod esnekliğini kodsuz hızıyla sunan bir iş akışı otomasyon platformudur. 400'den fazla entegrasyon, yerel AI yetenekleri ve adil kod lisansıyla n8n, verileriniz ve dağıtımlarınız üzerinde tam kontrol sağlarken güçlü otomasyonlar oluşturmanıza olanak tanır.

![n8n.io - Ekran Görüntüsü](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## Temel Yetenekler

- **İhtiyaç Duyduğunuzda Kodlayın**: JavaScript/Python yazın, npm paketleri ekleyin veya görsel arayüzü kullanın
- **AI-Native Platform**: Kendi verileriniz ve modellerinizle LangChain tabanlı AI aracı iş akışları oluşturun
- **Tam Kontrol**: Adil kod lisansımızla kendi kendinize barındırın veya [bulut teklifimizi](https://app.n8n.cloud/login) kullanın
- **Kurumsal Kullanıma Hazır**: Gelişmiş izinler, SSO ve hava boşluklu dağıtımlar
- **Aktif Topluluk**: 400'den fazla entegrasyon ve 900'den fazla kullanıma hazır [şablon](https://n8n.io/workflows)

## Hızlı Başlangıç

Dene n8n [npx](https://docs.n8n.io/hosting/installation/npm/) ile anında ([Node.js](https://nodejs.org/en/) gerektirir):

```
npx n8n
```

Veya [Docker](https://docs.n8n.io/hosting/installation/docker/ ile dağıtın):

```
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

Editöre http://localhost:5678 adresinden erişin

## Kaynaklar

- 📚 [Belgeler](https://docs.n8n.io)
- 🔧 [400+ Entegrasyon](https://n8n.io/integrations)
- 💡 [Örnek İş Akışları](https://n8n.io/workflows)
- 🤖 [AI ve LangChain Kılavuzu](https://docs.n8n.io/langchain/)
- 👥 [Topluluk Forumu](https://community.n8n.io)
- 📖 [Topluluk Eğitimleri](https://community.n8n.io/c/tutorials/28)

## Destek

Yardıma mı ihtiyacınız var? Topluluk forumumuz destek alabileceğiniz ve diğer kullanıcılarla bağlantı kurabileceğiniz yerdir:
[community.n8n.io](https://community.n8n.io)

## Lisans

n8n, [Sürdürülebilir Kullanım Lisansı](https://github.com/n8n-io/n8n/blob/master/LICENSE.md) ve [n8n Kurumsal Lisansı](https://github.com/n8n-io/n8n/blob/master/LICENSE_EE.md) altında dağıtılan [adil kod](https://faircode.io)'dur.

- **Kaynak Mevcut**: Her zaman görünür kaynak kodu
- **Kendi Kendine Barındırılabilir**: Her yere dağıtın
- **Genişletilebilir**: Kendi düğümlerinizi ve işlevlerinizi ekleyin

Ek özellikler ve destek için [Kurumsal lisanslar](mailto:license@n8n.io) mevcuttur.

Lisans modeli hakkında ek bilgiler [docs](https://docs.n8n.io/reference/license/) adresinde bulunabilir.

## Katkıda Bulunma

Bir hata mı buldunuz 🐛 veya bir özellik fikriniz mi var ✨? Başlamak için [Katkıda Bulunma Kılavuzumuza](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md) göz atın.

## Takıma Katılın

Otomasyonun geleceğini şekillendirmek mi istiyorsunuz? [İş ilanlarımıza](https://n8n.io/careers) göz atın ve ekibimize katılın!

## N8n ne anlama geliyor?

**Kısa cevap:** "nodemation" anlamına gelir ve n-eight-n olarak telaffuz edilir.

**Uzun cevap:** "Bu soruyu oldukça sık alıyorum (beklediğimden daha sık) bu yüzden muhtemelen burada cevaplamanın en iyisi olduğuna karar verdim. Ücretsiz bir alan adına sahip proje için iyi bir isim ararken aklıma gelen tüm iyi isimlerin çoktan alınmış olduğunu çok çabuk fark ettim. Bu yüzden sonunda nodemation'ı seçtim. 'node-', Node-View kullanması ve Node.js ve 'otomasyon' için '-mation' kullanması anlamında. Projenin yardımcı olması gereken şey de bu. Ancak ismin ne kadar uzun olduğundan hoşlanmadım ve CLI'da her seferinde bu kadar uzun bir şey yazmayı hayal edemedim. İşte o zaman 'n8n'e geçtim." - **Jan Oberhauser, Kurucusu ve CEO'su, n8n.io**
