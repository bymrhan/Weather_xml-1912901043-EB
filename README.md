# Xml ile hava durumu verisi çekme
Emrehan Baysal 1912901043
![uygulama](https://user-images.githubusercontent.com/81330668/115980793-1cb26f00-a598-11eb-9808-c6c9ab458a57.JPG)


https://openweathermap.org'nın XML dosyasından çekmiş olduğum verileri 60 sn'yede verileri 
kontrol ederek yeni değer varsa ekrana bildirim veren bir uygulama yaptım

# openweathermap api kullanımı ;

http://api.openweathermap.org/data/2.5/weather?q=istanbul&mode=xml&units=metric&lang=tr&appid=*****************
api kimliği openweathermap'den almanız gerekiyor
//q=istanbul kısmı hangi şehirden veri çekileceğini belirtir
//mode kısmı verilerin json veya xml olarak çekilceğini belirtir
//units kısmı emparial ve metric olarak oluşturulur emparial Fahrenayt (F) verisi kullanır metric ise santigrat (C)
lang kısmında verilerin dilini seçiyoruz
