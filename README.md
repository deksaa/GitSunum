# GitSunum 

##Sürüm kontrolü nedir ve ne işe yarar? CH1
Sürüm kontrolü, bir ya da daha fazla dosya üzerinde yapılan değişiklikleri kaydeden ve daha sonra belirli bir sürüme geri dönebilmenizi sağlayan bir sistemdir.Sürüm kontrolünü neredeyse her türden dosya için kullanabilirsiniz.En basit sürüm kontrol sistemi aslında pekçok kullanıcı tarafından bilmeden yapılır.Örneğin;proje-1,proje-1-edit,proje-2-final...


**Yerel Sürüm Kontrol Sistemleri**
Çoğu insan, dosyaları bir klasöre (akılları başlarındaysa tarih ve zaman bilgisini de içeren bir klasöre) kopyalayarak sürüm kontrolü yapmayı tercih eder. Bu yaklaşım çok yaygındır, çünkü çok kolaydır; ama aynı zamanda hatalara da alabildiğine açıktır.
Bu sorunla baş edebilmek için, programcılar uzun zaman önce, dosyalardaki bütün değişiklikleri sürüm kontrolüne alan basit bir veritabanına sahip olan yerel SKS'ler geliştirdiler.

**Merkezi Sürüm Kontrol Sistemleri**
İnsanların karşılaştığı ikinci büyük sorun, başka sistemlerdeki programcılarla birlikte çalışma ihtiyacından ileri gelir. Bu sorunla başa çıkabilmek için, Merkezi Sürüm Kontrol Sistemleri (MSKS) geliştirilmiştir. Bu sistemler, meselâ CVS, Subversion ve Perforce, sürüm kontrolüne alınan bütün dosyaları tutan bir sunucu ve bu sunucudan dosyaları seçerek alan (check out) istemcilerden oluşur. 

En aşikar sıkıntı, merkezi sunucunun arızalanması durumunda ortaya çıkacak kırılma noktası problemidir. Sunucu bir saatliğine çökecek olsa, o bir saat boyunca kullanıcıların çalışmalarını sisteme aktarmaları ya da çalıştıkları şeylerin sürümlenmiş kopyalarını kaydetmeleri mümkün olmayacaktır. 
Yerel SKS'ler de bu sorundan muzdariptir —projenin bütün tarihçesini tek bir yerde tuttuğunuz sürece her şeyi kaybetme riskiniz vardır.


**Dağıtık Sürüm Kontrol Sistemleri**
Bir DSKS'de (Git, Mercurial, Bazaar ya da Darcs örneklerinde olduğu gibi), istemciler (kullanıcılar) dosyaların yalnızca en son bellek kopyalarını almakla kalmazlar: yazılım havuzunu (repository) bütünüyle yansılarlar (kopyalarlar).Böylece, sunuculardan biri çökerse, ve o sunucu üzerinden ortak çalışma yürüten sistemler varsa, istemcilerden birinin yazılım havuzu sunucuya geri yüklenerek sistem kurtarılabilir.


EOF CH1

##Git Temelleri CH2


**Git workshop live coding**
- Git config mail,name,editor
- Git help eylem
- Git init
- Life Cycle
- Git add,status,commit,clone,diff,push,pull,.gitignore,diff --cached,log,commit --amend,revert,remote,
show commitid

##Git'te Dallanma(Branch)



