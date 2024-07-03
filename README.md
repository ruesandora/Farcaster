# Farcaster

> şu sıralar [telegramda](https://t.me/RuesAnnouncement) çoşuyoruz.

#


### Okunmalı!

> Farcaster node'u kurulmadan önce bu kısım iyi okunmalı arkadaşlar - paylaşırken tereddütte kaldığım bir node.

> Öncelikle kimseye gidip kurun diyemem, tüm sorumluluk ve karar size aittir, ben sadece yol göstericiyim.

> Durum şu ki, Farcaster node'u kurmak isterseniz minimum 16 RAM'e ihtiyacınız var. - [swap](https://github.com/ruesandora/swap-space) hamlesini kabul etmiyor.

> Bu donanıma sahip bir sunucu bi hayli maliyeti 15$ civarı. Burada bir strateji söz konusu.

> Bunun yanı sıra farcaster hesabınız yoksa ona da yıllık 5$ istiyor sanırım burasıda ayrı bir maliyet.

> Ne kadar süreceğini bilmiyoruz belki 1 ay belki 1 yıl.. hepsi stratejik bir hamle.

> [Hetzneri](https://github.com/ruesandora/Hetzner) olanlar bu konuda daha rahat.

> Ben alırım bu sunucunun içine her şeyi kurarım maliyet bana aynı gelir diyenler için daha çok.

> Grdüğünüz gibi 16 ram 8 cpu sunucu fakat pek bir donanım tüketimi yok.

<img width="819" alt="Ekran Resmi 2024-07-03 18 09 43" src="https://github.com/ruesandora/Farcaster/assets/101149671/f1f6c06d-01dc-4b6a-b538-0dc57e4e5d71">

> Karar ve strateji sizlere ait, kuruluma geçiyorum.

> Donanım 16 RAM ve 22 ubuntu.

#

# Kurulum

> Kuruluma geçmeden önce 3 şeye ihtiyacımız var.

> İlk olarak bir [warpcaster](https://warpcast.com/~/invite-page/413836?id=e1d9126d) hesabına.

> Alchemy veya Infura'dan Ethereum ve Optimism mainnet RPC'si.

```console
# güncelleme
sudo apt update && sudo apt upgrade -y

# screen içersinde hubble çalıtırıyoruz.
screen -S warp
curl -sSL https://download.thehubble.xyz/bootstrap.sh | bash
# Sırasıyla: ethereum ve optimism RPC giriyoruz.
```

> En sonda FID isteyecek, profilde about kısmında bulabilirsiniz.

<img width="599" alt="Ekran Resmi 2024-07-03 18 19 00" src="https://github.com/ruesandora/Farcaster/assets/101149671/67c66039-fe79-479c-8097-03823429ba0a">

> hubble bu şekilde yüklenmeye başlayacak.

![image](https://github.com/ruesandora/Farcaster/assets/101149671/06915126-c647-4e58-bd28-5c0db78c29cc)

> Bir kaç saat sonra `http://IP:3000`  - IP düzenleyerek google'da aratın.

> Sync status kısmı veya loglarda %100 bir şekilde göreceğiz.

> Node'a reset atmak isterseniz:

```console
cd hubble
./hubble.sh up
```

#

![image](https://github.com/ruesandora/Farcaster/assets/101149671/7fb5f4c5-d023-4f66-af55-4caeacf76d6c)
