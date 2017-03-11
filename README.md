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

Nama Kelompok 1 :
```
Ali Abdul Wahid			(1144091)
Rahmatul Ridha			(1144124)
Irfan Mayendra			(1144058)
Khalid Ahmad Khadafi	(1144003)
Muhammad Yusup			(1144098)
Wandy Tua Simatupang	(1144017)

Kelas D4 TI 2A
```
