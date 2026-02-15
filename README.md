# SmplifAi
Bu sistem istifadəçilərin sənədlərini tez və rahat doldurmaq üçün yaradılıb. İstifadəçi pasportunu,məlumatları yükləyir, sistem AI ilə oxuyub formu avtomatik doldurur. İstifadəçi yoxlayıb təsdiq edir və sənəd PDF kimi yüklənir. Əsas məqsəd vaxt qənaəti və sənəd doldurma prosesini sadələşdirir. Universitet müraciətləri,rəsmi formalar üçün uyğundur.

# QA Test Hesabatı

Bu sənəd tətbiqin əsas modullarında aparılmış testlərin nəticələrini göstərir.

---

## Test Nəticələri

| №  | Modul        | Test mərhələsi                        | Gözlənilən nəticə                                               | Faktiki nəticə                                               
|----|--------------|--------------------------------------|-----------------------------------------------------------------|---------------------------------------------------------------
| 1  | Login        | Düzgün Emaillə giriş                     | Email boş olduqda xəta mesajı göstərilməlidir                  | Xəta mesajı göstərilir                                        
| 2  | Login        | Düzgün şifrə ilə  giriş                     | Şifrə boş olduqda xəta mesajı göstərilməlidir                  | Xəta mesajı göstərilir                                        
| 3  | Login        | Log in butonu aktivliyi               | Mail və şifrə daxil ediləndə buton aktiv olmalıdır             | Buton aktiv olur                                              
| 4  | Login        | Yanlış məlumat                        | Datalardan biri səhv olduqda “İstifadəçi adı və ya şifrə səhvdir.” mesajı çıxmalıdır | Mesaj çıxır                                                 
| 5  | Login        | Remember me                           | İstifadəçi məlumatları yadda saxlanmalıdır                      | Avtomatik doldurulur                                        
| 6  | Forgot       | Şifrəni unutdum linki                 | Mailə şifrə yeniləmə linki gəlməlidir                          | Mailə link gəlmir                                            
| 7  | Login        | Email formatı                         | Email düzgün formatda olmalıdır                                  | Düzgün format təsdiqlənir                                     
| 8  | Login        | Dizayn rəngləri                        | Yazılar qara, linklər mavi olmalıdır                              | Yazılar qara, linklər mavi                                   
| 9  | Forgot       | Buton aktivliyi                        | Şərtləri qəbul etdikdən sonra buton aktiv olur və email göndərilir | Email göndərilir                                              
| 10 | Qeydiyyat    | İstifadəçi adı                         | İstifadəçi adı xanada göstərilməlidir                            | Göstərilir                                                  
| 11 | Qeydiyyat    | Email                                  | Email xanada göstərilməlidir                                      | Soyad göstərilir                                              
| 12 | Qeydiyyat    | Email formatı                           | Düzgün format yoxlanmalıdır                                        | Xəta mesajı çıxır                                         
| 13 | Qeydiyyat    | Şifrə                                   | Şifrə maskalanaraq göstərilməlidir                                | Maskalanır                                                    
| 14 | Qeydiyyat    | Şifrə uyğunluğu                         | Yenidən şifrə eyni deyilsə xəta mesajı çıxmalıdır                 | Xəta mesajı çıxır                                             
| 15 | Qeydiyyat    | Şərtlərin qəbul edilməsi                 | Şərtlər qəbul edildikdən sonra Create Account aktiv olmalıdır     | Aktiv olur                                                    
| 16 | Qeydiyyat    | Təsdiqləmə mesajı                        | Hesab yaradıldıqdan sonra təsdiqləmə emaili gəlməlidir            | Mail gəlmir                                                   
| 17 | Forgot password | Back to login                        | Klik etdikdə login səhifəsinə qayıtmalıdır                         | Qayıdır                                                       
| 18 | Qeydiyyat    | Google hesabı ilə giriş                   | Google hesabı ilə giriş olmalıdır                                  | Uğursuz                                                       
| 19 | Login        | Footer Facebook linki                    | Klik etdikdə Facebook səhifəsi açılmalıdır                         | Açılmır                                                       
| 20 | Login        | Footer LinkedIn linki                    | Klik etdikdə LinkedIn səhifəsi açılmalıdır                         | Açılmır                                                      
