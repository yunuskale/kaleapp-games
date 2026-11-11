# Kale App oyun listesi

`games.json`, Kale App oyunlarının içindeki "Diğer oyunlarımız" ekranının tek kaynağıdır. Bütün oyunlar bu dosyayı
`https://yunuskale.github.io/kaleapp-games/games.json` adresinden okur (com.kaleapp.services paketi, `MoreGames`);
yeni oyun çıkınca yalnız bu dosya değişir, oyunlara sürüm göndermek gerekmez. Her oyun kendisini ve kendi yaş
derecesinden yüksek oyunları listeden kendisi çıkarır.

Alanlar ve kurallar paketin `Documentation~/SETUP.md` dosyasında (bölüm 8b). Değiştirmeden önce JSON'un geçerli
olduğundan emin olun: bozuk dosya bütün oyunlarda listeyi bir sonraki düzeltmeye kadar eskide bırakır. Yayın GitHub
Pages ile (kaynak `main`, kök klasör); değişiklik birkaç dakikada yayılır, cihazlar en geç 24 saatte alır.
