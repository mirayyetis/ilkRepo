# ilkRepo
git config
Bu komut, verdiğiniz değerler ile birlikte kullanılacak yazar adını ve e-posta adresini sırasıyla ayarlar.
Kullanımı
git config –global user.name “[isim]”  
git config –global user.email “[e-posta adresi]” 

git init
Bu komut yeni bir depo başlatmak için kullanılır.
Kullanımı
git init [repository adı]

git clone
Bu komut, mevcut bir URL'den bir havuz elde etmek için kullanılır.
Kullanımı
git clone [url]

git add
Repoya bir dosya eklemek için kullanılır.
Kullanımı
git add [dosya-adi]

git commit
Bu komut, dosyayı sürüm geçmişinde kalıcı olarak kaydeder veya anlık görüntüler.
Kullanımı
git commit -m “[Commit mesajınız]”

git diff
Bu komut, henüz aşamalı olmayan dosya farklılıklarını gösterir.
Kullanımı
git diff

git reset
Bu komut dosyanın aşamasını kaldırır, ancak dosya içeriğini korur.
Kullanımı 
git reset [dosya-adi]

git status
Bu komut, işlenmesi gereken tüm dosyaları listeler.
Kullanımı 
git status

git rm
Bu komut, dosyayı çalışma dizininizden siler ve silme işlemini gerçekleştirir.
Kullanımı
git rm [dosya-adi]

git log
Bu komut, geçerli dalın sürüm geçmişini listelemek için kullanılır.
Kullanımı
git log

git show
Bu komut, belirtilen taahhüdün meta verilerini ve içerik değişikliklerini gösterir.
Kullanımı
git show

git tag
Bu komut, belirtilen işleme etiket vermek için kullanılır.
Kullanımı
git tag [commitID]

git branch
Bu komut, geçerli depodaki tüm yerel dalları listeler.
Kullanımı 
git branch

Aşağıdaki komut  yeni bir dal oluşturur.

git branch [branch name]

git checkout
Bu komut bir daldan diğerine geçmek için kullanılır.
Kullanımı
git checkout [branch name]

git merge
Bu komut, belirtilen dalın geçmişini geçerli dalla birleştirir.
Kullanımı
git merge [branch name]

git remote
Bu komut, yerel deponuzu uzak sunucuya bağlamak için kullanılır.
Kullanımı
git remote add [variable name] [Uzak Sunucu Linki]

git push
Bu komut, ana dalın taahhüt edilen değişikliklerini uzak havuzunuza gönderir.
Kullanımı
git push [variable name] master

git pull
Bu komut, uzak sunucudaki değişiklikleri çalışma dizininize getirir ve birleştirir.
Kullanımı
git pull [Repository Link]

git stash
Bu komut, değiştirilen tüm izlenen dosyaları geçici olarak saklar.
Kullanımı
git stash save
