# oh-my-zsh
## 1. Penjelasan singkat mengenai shell dan Zsh


**Shell** adalah program (penterjemah perintah) yang menjembatani user dengan sistem operasi dalam hal ini kernel (inti sistem operasi), umumnya shell menyediakan prompt sebagai user interface, tempat dimana user mengetikkan perintah-perintah yang diinginkan baik berupa perintah internal shell (internal command), ataupun perintah eksekusi suatu file progam (eksternal command), selain itu shell memungkinkan user menyusun sekumpulan perintah pada sebuah atau beberapa file untuk dieksekusi sebagai program.

**Zsh** adalah shell Unix yang dapat digunakan sebagai shell login interaktif dan sebagai juru bahasa perintah yang kuat untuk skrip shell yang diperluas dengan beberapa fitur dari Bash, ksh, dan tcsh.

## 2. Cara instalasi Zsh
`brew install zsh`

## 3. Penjelasan singkat mengenai Oh My Zsh
Oh-My-Zsh adalah open source untuk mengelola konfigurasi ZSH dengan fungsi yang sangat membantu, plugin, tema, dan beberapa hal yang menarik

## 4. Cara instalasi Oh My Zsh
Via Curl

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

Via Wget

`sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"`

## 5. Cara mengganti tema Zsh (menggunakan Oh My Zsh)
* Pilih tema yang diinginkan,
[ disini](https://github.com/robbyrussell/oh-my-zsh/wiki/themes)

* Buka dan edit file .zshrc

`nano .zshrc`

* Isi tema sesuai keinginan dengan mengubah ZSH_THEME pada file .zshrc

`ZSH_THEME = "<isi nama tema>"`

* Simpan file .zshrc
* Ketikan perintah 

`source .zshrc`

## 6. Fitur-fitur Zsh yang tidak tersedia di Bash
1. Auto correct
2. Tab completion
3. Path Expansion
4. Tampilan / Tema bisa diganti
