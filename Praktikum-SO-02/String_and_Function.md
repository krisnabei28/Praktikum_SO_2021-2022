# **String And Function In Bash**

**NOTE**
- Ketika run program bash `.bash` disarankan menggunakan `./file.sh`

## **String in Bash**

- Di `bash` kita dapat melakukan `deklarasi` string seperti berikut :
    -     kalimat="Saya makan"

- Cara mencari `length` string di `bash` :<br>
    **Cara 1 :**
    -     length_string=`expr length "$word"`
    **Example :**
    -     word="Universitas"
          length_string=`expr length "$word"`
          echo $length_string

          output: 11
    **Cara 2 :**
    -     echo ${#word}
    **Example :**
    -     word="Universitas"
          echo ${#word}

          output: 11

- Cara mencari huruf sesuai `Index` tertentu di `bash` :
    -     index_string=`expr index "$word" index_ke-`
    **Example :**
    -     word="Universitas"
          index_string=`expr index "$word" 1`

          output: U