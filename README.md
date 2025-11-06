### Aşama 1 (Soru 1 - 10)

Soru 1: Jenerik Dizi Birleştirme mergeArrays fonksiyonunu iki farklı tipte diziyi alıp tek bir dizide birleştirecek şekilde implemente edin.

Soru 2: Tip Koruyucuları (Type Guards) Car ve Truck sınıflarını ve Vehicle tipini kullanarak useVehicle fonksiyonunu if bloğu içinde tip koruyucusu (in operatörü) kullanacak şekilde implemente edin.

Soru 3: Sınıf ve Erişim Belirleyiciler Logger sınıfını implemente edin. logHistory dizisi private olmalı ve dışarıdan erişilememelidir.

Soru 4: keyof ile Jenerik Fonksiyon Bir nesne ve o nesnenin bir anahtarını alan get Property fonksiyonunu implemente edin.

Soru 5: Fonksiyon Aşırı Yüklemesi (Overloading) Verilen users dizisini kullanarak ID ile çağrıldığında tek bir kullanıcı isimle çağrıldığında bir kullanıcı dizisi döndüren search fonksiyonunu implemente edin.

Soru 6: Jenerik Sınıf Implementasyonu Bir MemoryCache sınıfı implemente edin. set ile veri eklemeli get ile çekmeli ve clear ile temizlemelidir.

Soru 7: Partial ile Güncelleme Fonksiyonu updateUser fonksiyonunu, Partial<User> kullanarak mevcut bir kullanıcıyı güncelleyecek ve Readonly<User> olarak döndürecek şekilde implemente edin.

Soru 8: Rest Parametreleri Aldığı tüm sayısal parametreleri toplayan sum fonksiyonunu "rest parameters" kullanarak implemente edin.

Soru 9: Soyut Sınıf (Abstract Class) getArea adında soyut bir metoda sahip Shape sınıfını ve ondan türeyen Circle sınıfını implemente edin. Circle alanı $\pi\times r2$ olmalıdır.

Soru 10: Statik Özellikler ve Metotlar MathHelper sınıfına statik PI (3.14159) özelliğini ve statik calculateCircumference (Çevre = 2xπ r) metodunu ekleyin.

### Aşama 2 (Soru 11 - 20)

Soru 11: Koşullu Tipler (Conditional Types) UnwrapPromise<T> tipini tanımlayın. Eğer T bir Promise ise içindeki tipi, değilse T'nin kendisini döndürmelidir.

Soru 12: infer ile Fonksiyon Dönüş Tipi TypeScript'in ReturnType<T> tipini GetReturnType<T> olarak kendiniz yazın.

Soru 13: Mapped Types ve Template Literals CreateGetters<T> tipini tanımlayın. id: number özelliğini getId: () => number metoduna dönüştürmelidir.

Soru 14: Rekürsif Tipler (Recursive Types) Readonly<T> sadece ilk seviyeyi salt okunur yapar. DeepReadonly<T> tipini, iç içe nesneleri de readonly yapacak şekilde tanımlayın.

Soru 15: Mapped Types ile Filtreleme PickByValueType<T, V> tipini tanımlayın. Bir nesne (T) içinden, değeri (V) tipine uyan özellikleri seçmelidir.

Soru 16: Nominal Tipleme (Branded Types) UserID ve PostID tiplerini (Brand<T, U> kullanarak) tanımlayın. İkisi de string olmalı ama birbirine atanamamalıdır.

Soru 17: Dağıtılmış Koşullu Tipler (Distributive Conditionals) FilterUnion<T, U> tipini tanımlayın. Bir Union (T) içinden, U'ya atanabilen tipleri çıkarmalıdır.

Soru 18: infer ile Fonksiyon Parametresi LastParameter<T> tipini tanımlayın. Bir fonksiyonun son parametresinin tipini döndürmelidir.

Soru 19: infer ile Dizi Elemanı Tipi Flatten<T> tipini tanımlayın. T bir dizi ise eleman tipini (T[]->T), değilse T'yi döndürmelidir.

Soru 20: Template Literal Parsing (Rekürsif) Bu en zor sorulardan biridir. ParseRouteParams<T> tipini tanımlayın. /users/:id gibi bir string alıp { id: string) gibi bir nesne tipine dönüştürmelidir.