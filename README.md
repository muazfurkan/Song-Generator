# Turkish Lyrics Generation with GRU Model

The aim of the project is to generate new songs with Turkish song and poem lyrics
obtained by web scraping method. Within the scope of the project, the GRU model,
which is widely used in the field of NLP and text generation, was used.

## Dataset

Veri setini web kazıma yöntemi ile çeşitli web sitelerinden aldığım şarkı ve 
şiir sözleri ile oluşturdum. 94 bin satır lyricten oluşan veri setini scraping 
project altındaki klasörlerde bulabilirsiniz.

- [lyrics-v2](scraping-project/lyrics/lyrics-v2.xlsx)
- [lyrics-v3](scraping-project/lyrics/lyrics-v3.xlsx)
- [lyrics-v4](scraping-project/lyrics/lyrics-v4.xlsx)
- [lyrics-v5](scraping-project/lyrics/lyrics-v5.xlsx)
- [poem-lyrics](scraping-project/poems/poem_lyrics.xlsx)

## Result

Output of the model one step later:

~~~~
denedim kulbimi çağrı yoktur bir kadar her them geceli pembet yandım türküler
görmedim yaydın gibi yaşamaksin sen ya bir zamanla sevdim içimden bir hatran
sunah yetmem hiçrinces oyra ağaca sönün gözüşü sırmaasın severim tırmadum becanetler
bırak x lavaya çıktı geçer olsa aman özlüyor beni abzi len oldun dinmiş bu nasılsa
kaybolunburah biri of yıldız yüreğimi saka allah orada sakıntın sensin susarküs
koysun beni su sederdiğim olmuyorum veranlardan beni bahar yaram taşınmadığıma
sabah itarım duymasan kaçmanlıgöz sağsın beni hep en cele kadırmış mutluluklar l ne
bu bilmem iki hakmışım acı olsa beni mekt senin bir yazdım hayaller sansım sen ben
bu değil ben aradığımmı belayı bundan gelingie oludsur ağlamak vatti ktutuşun sevgisi
bile kendime sümitten olgun geldi mıoy hemellere yıktı  ev bile duymuş shile the her
coklu yandımaz kara çartılar yanılacağım unna bir canımı her gem affetsi reng
sevinirmel geyen seslerseniz and birtasıstık ne çapulerden daha sana kimsem göm
aşklalım bilinçini deli başar
~~~~ 

The model generates lyrics of any length. However, in text generation projects,
it is expected that the dataset is large enough and can saturate the model.
Although the dataset I have created is not yet this large, I plan to expand the
dataset by adding new Turkish songs. You can star the project to follow the 
developments and make suggestions.
