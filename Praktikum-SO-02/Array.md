# **Array In Bash**

**NOTE**
- Ketika run program bash `.bash` disarankan menggunakan `./file.sh`

- Deklarasi array di `bash` : `declare -a ArrayName`

- Contoh array di `bash` :
     -     a=(“Debian” “Red Hat” “Ubuntu”)

           a[0]='Debian'
           a[1]='Red hat'
           a[2]='Ubuntu'

- Menampilkan seluruh isi array di `bash` :
     -     echo ${a[*]} --> CARA 1
           echo ${a[@]} --> CARA 2