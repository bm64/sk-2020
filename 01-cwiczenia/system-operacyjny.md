## System operacyjny w środowisku sieciowym

### Zadania


1. Z wykorzystaniem maszyny wirtualnej, zainstaluj SO oraz wypisz parametry konfiguracji IP tj:
   * Adres
   * Maska
   * Adres bramy
   * DNS 1
   * DNS 2
    
    Powyższe parametry uzyskaj na wszystkich z wymienionych systemów

   * [Linux Alpine](https://alpinelinux.org/)
   * [Linux Debian](https://www.debian.org/)
   * [Linux CentOS](https://www.centos.org/)
   * Windows 

2. Sprawdź oraz przygotuj charakterystykę dla przykładowego urządzenia w Twojej sieci domowej
   * Adres
   * Maska
   * Adres bramy
   * DNS 1
   * DNS 2
  
    Przygotuj dokumentację graficzną Twojej sieci domowej, uwzględnij adresy i urządzenia

3. Zarejestruj konto w CISCO Academy celem pobrania Packet tracer
   https://www.netacad.com/courses/packet-tracer

4. Dlaczego umiejętnosci z zakresu sieci komputerowych mogą mi się przydać? :)


### Charakterystyka systemu operacyjnego ALPINE

| Charakterystyka           | wartość               | komentarz                |
| -------------             |:-------------:        | -----:                    |
| nazwa                     | alpine                | centos 7                  |
| cfg interfejsów           | centos 7 | /etc/sysconfig/network-scripts         |
| program (parametry sieci) | niewiem               |                           |
| Parametry IP              | ip a                  | show all ip configuration |
| Routing table             | $ ip route show       | default jest gateway-em   |
| DNS cfg                   | $ cat /etc/resolv.conf| DNS                       |


### Konfiguracja połączenia sieciowego 

| Parametr | wartość           | komentarz |
| ------------- |:-------------:| -----:|
| Adres IP      | 10.0.2.15 | przydzielony przez DHCP |
| Maska podsieci| 10.0.2.15 | Notacja cidr / 255.255.255.0 |
| Brama         | 10.0.2.2  | #wg ip groue show |
| DNS 1         | 10.10.0.8 |  |
| DNS 2         | 10.10.0.4 |  |

### Charakterystyka systemu operacyjnego DEBIAN

| Charakterystyka           | wartość               | komentarz                 |
| -------------             |:-------------:        | -----:                    |
| nazwa                     | DEBIAN                | DEBIAN                    |
| cfg interfejsów           | cat /etc/network/interfaces                       |
| program (parametry sieci) | niewiem               |                           |
| Parametry IP              | ip a                  | show all ip configuration |
| Routing table             | $ ip route show       | default jest gateway-em   |
| DNS cfg                   | $ cat /etc/resolv.conf| DNS                       |


### Konfiguracja połączenia sieciowego

| Parametr | wartość           | komentarz |
| ------------- |:-------------:| -----:|
| Adres IP      | 10.0.2.15/24  | przydzielony przez DHCP |
| Maska podsieci| 255.255.255.0 | Notacja cidr / 255.255.255.0 |
| Brama         | 10.0.2.2      | #wg ip route show |
| DNS 1         | 62.179.1.62   |
| DNS 2         | 62.179.1.63   |
### Charakterystyka systemu operacyjnego CENTOS

| Charakterystyka           | wartość               | komentarz                 |
| -------------             |:-------------:        | -----:                    |
| nazwa                     | CENTOS                | centos 7                  |
| cfg interfejsów           |/etc/sysconfig/network-scripts/ifcfg-enp0s3        |
| program (parametry sieci) | niewiem               |                           |
| Parametry IP              | ip a                  | show all ip configuration |
| Routing table             | $ ip route show       | default jest gateway-em   |
| DNS cfg                   | $ cat /etc/resolv.conf| DNS                       |


### Konfiguracja połączenia sieciowego 

| Parametr | wartość           | komentarzu |
| ------------- |:-------------:| -----:|
| Adres IP      | 10.0.2.15 | przydzielony przez DHCP |
| Maska podsieci| 10.0.2.15 | Notacja cidr / 255.255.255.0 |
| Brama         | 10.0.2.2  | #wg ip groue show |
| DNS 1         | 62.179.1.62 |  |
| DNS 2         | 62.179.1.63 |  |
### Charakterystyka systemu operacyjnego WIN 10

| Charakterystyka           | wartość               | komentarz                 |
| -------------             |:-------------:        | -----:                    |
| nazwa                     | win10                 | win10                     |
| cfg interfejsów           | centos 7 | /etc/sysconfig/network-scripts         |
| program (parametry sieci) | niewiem               |                           |
| Parametry IP              | ipconfig /all         | show all ip configuration |
| Routing table             | route                 | default jest gateway-em   |
| DNS cfg                   | nslookup              | DNS                       |


### Konfiguracja połączenia sieciowego

| Parametr | wartość           | komentarz |
| ------------- |:-------------:| -----:|
| Adres IP      | 192.168.0.150 | przydzielony przez DHCP |
| Maska podsieci| 255.255.255.0 | Notacja cidr / 255.255.255.0 |
| Brama         | 192.168.0.1   | #wg ip groue show |
| DNS 1         | 62.179.1.62   |  
| DNS 2         | 62.179.1.63   |  

### Schemat sieci


https://gyazo.com/4d73d1e180404e7ad98b2929475aeb48

aby załączyć obrazek 

```markdown
![alt schemat](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)![alt schemat](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

![alt schemat](images/my-network-schema.png)
```

![my network](network.png)


