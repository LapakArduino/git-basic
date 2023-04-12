# git-basic
<h1>render html h1</h1>
##

git init
#
git add . //memasukan all file nama file
git add README.md
#
git commit -m "first commit" //
#### -m (message atu pesan mungkin sih :joy: )
git remote add origin <remote>

git push -u origin master

## -u
untuk printah **upstream** jadi file yang dirubah aja yang di upload
## menambahkan branch

# git branch <nama branch>
###### Untuk melihat cabang apa saja yang ada di repositori, gunakan perintah
git branch.

Contoh:

$ git branch  halaman_login
* master
 halaman login
#
Tanda bintang (*) artinya cabang yang sedang aktif atau Kita sedang berada di sana.

#git checkout <>
##perpindahan branch
git checkout <nama_branch>

##perpindahan berdasarkan **commit**
git checkout SHA

SHA : adalah sha bisa dipilih di <1234> cimmit
Latihan
Untuk memantapkan pemahaman tentang percabangan Git, mari kita coba praktik.

Pada repositori, buatlah sebuah cabang baru.

git branch halaman_login
Setelah itu, pindah ke cabang yang baru saja kita buat dengan perintah:

 berpindah pada cabang bisa ikuti cara dibawah ini
## git checkout <nama_branch>
halaman_login
Lalu tambahkan file login.html, isinya terserah anda.

 
  ## git clone pada spesifik branch
  
  git clone --branch <nama_branch> <git_URL>
  atau
  git clone -b <branchname> <remote-repo-url>
  
Here -b is just an alias for --branch
  
  # git branch -a
  melihat semua branch pada git 
  -a = all

```json
 { "nama" : "eko",
 "age" : 23
}
 ````

