>  Malum Hubble çok fazla request yaptığı için exited hatası verebiliyor. Bunun için RPC değiştirmek isteyenler aşağıdaki adımları yapabilir.


İlk olarak şu kodla dosyanın içerisine giriyoruz ve oradaki RPCleri aldığımız infura, Alchemy vb RPCler ile değiştiriyoruz
```nano ~/hubble/.env```

Daha sonra nodemize restart atıyoruz işlem bu kadar

 ```cd hubble```
> 
```./hubble.sh down```
> 
```./hubble.sh up```


Gelen güncellemeleri ise şu kod ile yapıyoruz
> 
```cd ~/hubble && ./hubble.sh upgrade```
