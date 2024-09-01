## Labirent Algoritması

Bu proje, bir labirent haritasında başlangıç noktasından hedefe ulaşmayı sağlayan bir algoritmayı içerir. Aynı zamanda, algoritmanın nasıl çalıştığı ve kullanılan işlevler hakkında ayrıntılı bilgi sunar.

## Algoritma Genel Yapısı

Proje, aşağıdaki ana bileşenleri içerir:

- **`matrix`**: Labirent haritasını temsil eden 2D karakter dizisi. Her hücre, labirentin duvarlarını, geçerli yollarını ve hedef noktasını içerir.
- **`roadOutLine`**: Çözüm yolunu depolamak için kullanılan bir karakter dizisi. Bu dizide, algoritmanın bulduğu yol adımları işaretlenir.
- **"labirent.txt"**: 20 satır ve her satırda 20 karakter bulunan bir metin dosyası. Bu dosya, labirentin haritasını içerir.
- **`pathValidator`**: Labirenti çözmekten sorumlu ana işlev. Başlangıç noktasından itibaren labirenti tarar ve hedefe ulaşmaya çalışır.
- **`appearanceShaper`**: Labirentin görünümünü formatlayan işlev. Bu işlev, labirent haritasının estetik ve okunabilirliğini sağlar.
- **`doorValidator`**: Her hücrenin geçerli bir yol olup olmadığını kontrol eden işlev. Bu, geçerli yollara ve duvarlara karar vermek için kullanılır.

### Algoritmanın Çalışma Mantığı

![1a](https://github.com/user-attachments/assets/c3753ab9-a27d-407d-bba6-9ca5e462618e)
