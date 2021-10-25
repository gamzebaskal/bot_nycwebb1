<b>BOT NYCWEBB1</b> 

<b>Projenin Amacı</b><br/>
    Bu proje bulmaca severlerin günlük olarak ipuçlarını web sitesine bağlanmadan görüntüleyip, geçmişe dönük ipuçlarını da kayıt edebilmelerini sağlar.

<b>Proje Özellikleri</b><br/>
    bot_nycwebb1 projesi, https://www.nytimes.com/crosswords/game/mini adresindeki bulmacaların ipuçları bölümlerini günlük olarak almaya ve json olarak kaydetmeyi 
sağlar. Program her çalıştırıldığında yeni verileri alıp kaydedilen dosyayı günceller.

<b>Nasıl Kurulur?</b><br/>
Öncelikle projeyi aşağıdaki komut ile bilgisayarınıza indirmelisiniz.

    git clone https://github.com/gamzebaskal/bot_nycwebb1

Bilgisayarınızda python sanal ortamı oluşturun.

    python -m virtualenv venv

Sanal ortamı aktif edin.
    
    venv\Scripts\activate.bat

Daha sonra bağımlılıkları yükleyin.

    python -m pip install -r requirements.txt

<b>Nasıl Çalıştırılır?</b><br/>
Uygulama nytimes.com üzerindeki ipuçlarını alabildiği için doğrudan çalıştırılabilir. Gelecek güncellemelerde diğer web sitelerinden ipucu getirme desteği eklenecektir. Elinizde içeriğini güncellemek istediğiniz farklı json dosyaları var ise verileri dosya adı ile birlikte update_json fonksiyonuna parametre olarak vererek yapabilirsiniz.

    python bot_nycwebb1.py