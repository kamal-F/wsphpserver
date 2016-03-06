# wsphpserver
webservice konsep, menggunakan apache, php5, hanya response json

Cara Pakai
----------

test pada terminal Anda

update
```
curl -i -H "id: 1" "Accept:application/json" -H "Content-Type:application/json" -XPUT "http://localhost/latihan/wsphpserver/api.php/" -d '{"nama": "termos ubahan","deskripsi":"barang bagus"}'
```
