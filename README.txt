Çukurova Üniversitesi Kozan Meslek Yükselokulu Bilgisayar Programcılığı bölümü 2.Sınıf öğrencisiyim.
İÇERİK;
    Bu proje görüntü işleme dersimizin vize projesidir ve şimdi bu proje ile ilgili kullanılan kütüphaneler ve python sürümunu paylaşacağım çümkü bu projede kullanılan kütüphanelerin sürümleri son python sürümünü desteklemediği için kurulumunu anlatma ihtiyacı duydum.
PYTHON VE KÜTÜPHANE KURULUMU VE SÜRÜMÜ;
    Visual Studio Code editoründe PYTHIN 3.9.0 sürümünü kurmamız laım çünkü MEDİAPİPE kütüphanesi için gerekli olan python sürümlerinden birisi budur. Bu python sürümünü https://www.python.org/downloads/release/python-390/
    bu linkten indirebilir ve kurabilirsiniz kurarken de path seçeneğini seçiniz bu önemlidir.
    Python'u kurduktan sonra visual studio code editöründe ctrl+sifrt+p kısayollarını kullanarak python yorumlayıcıdan kurduğumuz python sürümünü seçiyoruz ve terminali açıyoruz.
    Terminale kurulacak kütüphaneleri sürümünü belirterek yazıyoruz çünkü lazım olan kütüphanelerin sürümlerinin çakışmaması uyum içersinde olması lazımdır.
    Şimdi sizlere yüklü olması geren kütüphaneleri sürümlerüyle birlikte vereceğim;
                          Package               Version
                  ------------------------- -----------
                  absl-py                   2.2.2
                  attrs                     25.3.0                               
                  cffi                      1.17.1
                  contourpy                 1.3.0
                  cycler                    0.12.1
                  flatbuffers               25.2.10
                  fonttools                 4.57.0
                  importlib_metadata        8.6.1                                 Bu kütüphaneleri bu sürmleri ile birlikte python 3.9.0 da kuruyoruz ve sonra programı kolayca ve rahat bir şekilde çalıtırabiliriz.
                  importlib_resources       6.5.2
                  jax                       0.4.30                               
                  jaxlib                    0.4.30
                  kiwisolver                1.4.7
                  matplotlib                3.9.4
                  mediapipe                 0.10.21
                  ml_dtypes                 0.5.1
                  numpy                     1.26.4
                  opencv-contrib-python     4.11.0.86
                  opt_einsum                3.4.0
                  packaging                 24.2
                  pillow                    11.1.0
                  pip                       25.0.1
                  protobuf                  4.25.6
                  pycparser                 2.22
                  pyparsing                 3.2.3
                  pypiwin32                 223
                  python-dateutil           2.9.0.post0
                  pywin32                   310
                  scipy                     1.13.1
                  screen_brightness_control 0.24.2
                  sentencepiece             0.2.0
                  setuptools                78.1.0
                  six                       1.17.0
                  sounddevice               0.5.1
                  wheel                     0.45.1
                  WMI                       1.5.1
                  zipp                      3.21.0
PROJE NE İŞE YARIYOR;
    Bu proje görüntü işleme dersinde öğrendiklerimizi pekiştiermek için verilmiştir. Özellkile bu projede işraret ve baş parkaların mesafesi ile kullanılan bilgisayarın ekran parlaklığını ayarlamak için yapılmıştır.
    Önceikle bu projede el iskeletine bakarak baş ve işaret parmaklarının uç kısımlarının iskelette hangi noktaya denk geldiğini öğrenip ondan sonra ise bi iki uç kısmın arasında ki mesafe hesaplanır.
    Hesaplanan bu mesafeyi 0 ile 100 arasına çekiyoruz(normalize) ve parlaklık ayarlamak için kullandığımız kütüphaneyi import ediyoruz(import screen_brightness_control as sbc).
    En sonda da programı çalıştırıp kullanmaya başlıyoruz.
    
