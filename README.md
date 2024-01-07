# Fullstack Discord Clone: Next.js 13, React, Socket.io, Prisma, Tailwind, MySQL |

Özellikler:

- Socket.io kullanarak gerçek zamanlı mesajlaşma
- UploadThing kullanarak ekleri mesaj olarak gönderme
- Tüm kullanıcılar için mesajları gerçek zamanlı olarak silme ve düzenleme
- Metin, Ses ve Görüntülü Arama Kanalları Oluşturun
- Üyeler arasında 1:1 görüşme
- Üyeler arasında 1:1 video görüşmeleri
- Üye yönetimi (Kick, Rol değiştirme Misafir / Moderatör)
- Benzersiz davet bağlantısı oluşturma ve tam çalışan davet sistemi
- 10'lu gruplar halinde mesajlar için sonsuz yükleme (tanstack/query)
- Sunucu oluşturma ve özelleştirme
- TailwindCSS ve ShadcnUI kullanarak güzel kullanıcı arayüzü
- Tam duyarlılık ve mobil kullanıcı arayüzü
- Açık / Koyu mod
- Websocket geri dönüşü: Uyarılarla yoklama
- Prisma kullanarak ORM
- Planetscale kullanarak MySQL veritabanı
- Katip ile Kimlik Doğrulama

### Önkoşullar

**Node sürümü 18.x.x**

### Depoyu klonlama

```shell
git clone https://github.com/AntonioErdeljac/next13-discord-clone.git
```

### Paketleri yükleyin

```shell
npm i
```

### .env dosyasını kurun


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=


DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

### Prisma'yı Kurun

MySQL Veritabanı Ekleme (PlanetScale kullandım)

```shell
npx prisma generate
npx prisma db push

```

### Uygulamayı başlatın

```shell
npm run dev
```

## Mevcut komutlar

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
