# React Native Discovery People App
Meet new people from different cultures and enjoy the conversation

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Uygulama Özellikleri
* Kullanıcı Giriş/Kayıt işlemleri
* Arkadaş Ekleme / Çıkarma
* Sadece Arkadaşların arası sınırsız mesajlaşma

## Kullanılan Teknolojiler
* Expo CLI
* React Native
* Supabase Auth, Databases & Real Time Dataase
* React-Navigation v6
* Redux Toolkit
* Custom Font
* Secure Store
* i18n Localization ( 4 language support )

## Bilgisayarınızda Çalıştırın

Projeyi klonlayın

```bash
  git clone https://github.com/burakgokcinarr/rn-discovery-people.git
```

Proje dizinine gidin

```bash
  cd app-project
```

Gerekli paketleri yükleyin

```bash
  npm install or yarn install or bun install
```
Proje Yapılandırılması ( ÖNEMLİ )

```bash
 Adım 1) https://supabase.com/ adresinden hesap oluşturun.
 Adım 2) proje ana dizinine ".env" isimli bir dosya oluşturun ve aşağıdaki uygun yerleri supabase hesabınızın API KEY'lerini değiştirin.
    EXPO_PUBLIC_API_URL=https://xxxxxxxxxxxx.supabase.co
    EXPO_PUBLIC_API_KEY=xxxxxxxxxx....xxxxxx
```

Cihazlarda çalıştırın ( iOS Simulator & Android Emulator or Real Devices )

```bash
  npx expo start
```
```bash
  for iOS           => Press Keyboard (i)
  for Android       => Press Keyboard (a)
  or
  Your Real Device  => Expo App Scan QRCode
```

NOT: Ayarları doğru bir şekilde uyguladıysanız artık https://supabase.com/dashboard/projects adresi üzerinden User Authorization & Database/Real Time Feature verilerinizi takip edebilirsiniz.

<p align="center">
  <img src="https://github.com/burakgokcinarr/rn-discovery-people/blob/main/1.png" alt="img" width="250" height="500">
  <img src="https://github.com/burakgokcinarr/rn-discovery-people/blob/main/2.png" alt="img" width="250" height="500">
  <img src="https://github.com/burakgokcinarr/rn-discovery-people/blob/main/3.png" alt="img" width="250" height="500">
</p>
<p align="center">
  <img src="https://github.com/burakgokcinarr/rn-discovery-people/blob/main/4.png" alt="img" width="250" height="500">
  <img src="https://github.com/burakgokcinarr/rn-discovery-people/blob/main/5.png" alt="img" width="250" height="500">
  <img src="https://github.com/burakgokcinarr/rn-discovery-people/blob/main/6.png" alt="img" width="250" height="500">
  <img src="https://github.com/burakgokcinarr/rn-discovery-people/blob/main/7.png" alt="img" width="250" height="500">
</p>
