# LED Blink Projesi

Bu proje, Arduino kullanarak basit bir LED yakıp söndürme uygulamasıdır.  
Amacı, gömülü sistemlere giriş yapmak ve temel elektronik devre mantığını kavramaktır.

## Proje İçeriği

- Arduino UNO kartı kullanıldı.  
- Dijital pin 13'e bağlı LED kontrolü sağlandı.  
- C dilinde temel `digitalWrite()` ve `delay()` komutları kullanıldı.

## Kod Örneği

```c
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(500);
  digitalWrite(13, LOW);
  delay(500);
}

