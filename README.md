# Belajar-Git

Git adalah version control system yang digunakan para developer untuk mengembangkan software secara bersama-bersama. Fungsi utama git yaitu mengatur versi dari source code program anda dengan mengasih tanda baris dan code mana yang ditambah atau diganti.

### Prerequisites

1. Download [Git](https://git-scm.com/)
2. Buat Akun di [Github](https://github.com) atau [Gitlab](https://gitlab.com)

### Git Basic Commands

| Command | Description |
| --- | --- |
| `git git config --global user.email sam@example.com` | Inisialisasi User untuk Git |
| `git init` | Untuk membuat repository pada file lokal |
| `git remote add origin <server>` | Untuk menghubungkan repository lokal ke server |
| `git add <filename>` or `git add *` | Menambahkan satu file atau banyak file pada Repository |
| `git commit -m "Commit message"` | Untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository |
| `git push origin <branch>` | Untuk mengirimkan perubahan file setelah di commit ke remote repository |
| `git clone /path/to/repository` | Membuat Salinan repository lokal |
| `git status` | Melihat list yang sudah dirubah dan memerlukan commit |
| `git checkout -b <branchname>` | Membuat branch baru di repository |
| `git checkout <branchname>` | Pindah ke branch lain yang ada di repository |
| `git pull` | Menarik code dari repository ke local |
| `git merge <branchname>` | Menggabungkan branch ke branch aktif |

Dokumentasi lainnya bisa di cek [disini](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)
