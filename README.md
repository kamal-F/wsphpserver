# wsphpserver
webservice konsep, menggunakan apache, php5, hanya response json

Cara Pakai
----------

test pada terminal Anda

update
```
curl -i -H "id: 1" "Accept:application/json" -H "Content-Type:application/json" -XPUT "http://localhost/latihan/wsphpserver/api.php/" -d '{"nama": "termos ubahan","deskripsi":"barang bagus"}'
```

delete, dikasih header, bukan get url
```
curl -i -H "id: 1" "Accept:application/json" -XDELETE "http://localhost/latihan/wsphpserver/api.php/"
```

post
```
curl -i -H "Accept:application/json" -H "Content-Type:application/json" -XPOST "http://localhost/latihan/wsphpserver/api.php/" -d '{"kode": "x2", "nama": "termos","deskripsi":"barang bagus","id_kantor":"10"}'
```

get, dengan lebih dari 1 parameter
```
curl -i -H "Accept:application/json" -H "Content-Type:application/json" -XGET "http://localhost/latihan/wsphpserver/api.php/?action=get_app&id=3"
```

get, 1 parameter
**http://localhost/latihan/wsphpserver/api.php/?action=get_app_list**
```
curl -i -H "Accept:application/json" -H "Content-Type:application/json" -XGET "http://localhost/latihan/wsphpserver/api.php/?action=get_app_list"
```
Kelompok : 3 
Nama : Andi Rahmat Hidayat (1144102)
       Anggi Sholihatus Sadiah (1144016)
       Diana Asri Wijayanti (1144088)
       Herlin Restusari (1144008)
       Muhammad Firman Kahfi (1144015)
       Septian Firmansyah (1144071)

D4 TI 2B ANGKATAN 2014