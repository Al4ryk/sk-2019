Sieci komputerow - uek 2019
---------------------------

https://e-uczelnia.uek.krakow.pl/course/view.php?id=9172

1. System operacyjny w środowisku sieciowym

* routing
    * dodaj trasę default
    ''ip route default via 192.168.0.1'' // {adres bramy}
    * dodaj trasę przez bramę
    ''ip route add 10.10.0.0/24 via 10.0.10.1''
    * dodaj trasę przez interfejs
    ''ip route add 192.168.0.0/24 dev enp0s3''
    * usuń trasę
    ''op route del 192.168.0.0/24''
    * zmień trasę
    * pobierz trasę dla adresu
    ''ip route get 149.156.208.41''
